---
title: image-comparison
categories: ['java', 'algorithms', 'comparison']
---
## [image-comparison](https://github.com/romankh3/image-comparison)

### Published on Maven Central Java Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison. Can be used for automation QA tests.

Published on Maven Central and jCenter Java Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison. Can be used for automation qa tests. The Usages of the `image-comparison` can be found here [Usage Image Comparison](https://github.com/romankh3/usage-image-comparison)

*   Implementation is using only standard core language and platform features, no 3rd party libraries and plagiarized code is permitted.

*   Pixels (with the same coordinates in two images) can be visually similar, but have different values of RGB. 2 pixels are considered to be "different" if they differ more than `pixelToleranceLevel`(this configuration described below) from each other.

*   The output of the comparison is a copy of `actual` images. The differences are outlined with red rectangles as shown below.

*   Some parts of the image can be excluded from the comparison and drawn in the result image.

Article about growing `image-comparison` on habr: [How did the test task become a production library](https://habr.com/ru/post/475482/)
