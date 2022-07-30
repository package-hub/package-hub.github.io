---
title: codeigniter-model
categories: ['php', 'codeigniter3', 'model']
---
## [codeigniter-model](https://github.com/yidas/codeigniter-model)

### CodeIgniter 3 Active Record (ORM) Standard Model with Laravel Eloquent & Yii2 AR like


```php
$this->load->model('Posts_model');

// Create an Active Record
$post = new Posts_model;
$post->title = 'CI3'; // Equivalent to `$post['title'] = 'CI3';`
$post->save();

// Update the Active Record found by primary key
$post = $this->Posts_model->findOne(1);
if ($post) {
    $oldTitle = $post->title; // Equivalent to `$oldTitle = $post['title'];`
    $post->title = 'New CI3';
    $post->save();
}
```

> The pattern is similar to [Yii2 Active Record](https://www.yiiframework.com/doc/guide/2.0/en/db-active-record#active-record) and [Laravel Eloquent](https://laravel.com/docs/5.8/eloquent#inserting-and-updating-models)
