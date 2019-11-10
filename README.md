# Visual Composer Params

***checkbox***

```
array(
  'type' => 'checkbox',
  'heading' => __( 'Use theme default font family?', 'js_composer' ),
  'param_name' => 'use_theme_fonts',
  'value' => array( __( 'Yes', 'js_composer' ) => 'yes' ),
  'description' => __( 'Use font family from the theme.', 'js_composer' ),
)
```

***select/ dropdown***

```
array(
  'type' => 'dropdown',
  'heading' => __( 'Text source', 'js_composer' ),
  'param_name' => 'source',
  'value' => array(
    __( 'Custom text', 'js_composer' ) => '',
    __( 'Post or Page Title', 'js_composer' ) => 'post_title',
  ),
  'std' => '',
  'description' => __( 'Select text source.', 'js_composer' ),
),
```
      
