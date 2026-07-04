---
title: geared_pagination
categories: ['ruby']
---
## [geared_pagination](https://github.com/basecamp/geared_pagination)

### Paginate Active Record sets at variable speeds


Most pagination schemes use a fixed page size. Page 1 returns as many elements as page 2. But that's
frequently not the most sensible way to page through a large recordset when you care about serving the
initial request as quickly as possible. This is particularly the case when using the pagination scheme
in combination with an infinite scrolling UI.

Geared Pagination allows you to define different ratios. By default, we will return 15 elements on page 1,
30 on page 2, 50 on page 3, and 100 from page 4 and forward. This has proven to be a very sensible set of
ratios for much of the Basecamp UIs. But you can of course tweak the ratios, use fewer, or even none at all,
if a certain page calls for a fixed-rate scheme.

On JSON actions that set a page, we'll also automatically set Link and X-Total-Count headers for APIs
to be able to page through a recordset.
