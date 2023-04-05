# ttest_app

##### Description

`ttest_app`, T-test application determines if there is a significant difference between the means of two groups. It performs Student's t-test on the data.

##### Details
The input data should be log / VSN transformed.

The workflow has 2 operators:

* [t_test_operator](https://github.com/tercen/t_test_operator)
* [scale_operator](https://github.com/tercen/scale_operator)

T_test operator settings:
* detailed = True
* var.equal = True
* paired = False


Views:

* Volcano plot
* Significant treatment effects
