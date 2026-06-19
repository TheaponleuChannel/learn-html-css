# HTML Attributes

HTML attribute ប្រើសម្រាប់ផ្តល់ព័ត៌មានបន្ថែមទៅឱ្យ HTML element។ Attribute ត្រូវបានសរសេរនៅក្នុង opening tag។

## របៀបសរសេរ Attribute

```html
<tagname attribute="value">Content</tagname>
```

ឧទាហរណ៍៖

```html
<a href="https://example.com">Visit Example</a>
```

នៅទីនេះ `href` គឺជា attribute ដែលប្រាប់ link ថាត្រូវទៅកាន់ URL ណា។

## Attribute ដែលប្រើញឹកញាប់

### `href`

ប្រើជាមួយ `<a>` ដើម្បីកំណត់ទីតាំង link។

```html
<a href="https://google.com">Google</a>
```

### `src`

ប្រើជាមួយ `<img>` ដើម្បីកំណត់ទីតាំងរូបភាព។

```html
<img src="image.jpg" alt="My image">
```

### `alt`

ប្រើសម្រាប់ពិពណ៌នារូបភាព ប្រសិនបើរូបភាពមិនអាចបង្ហាញបាន។

```html
<img src="cat.jpg" alt="A small cat">
```

### `style`

ប្រើសម្រាប់បន្ថែម CSS style ដោយផ្ទាល់លើ element។

```html
<p style="color: blue;">This text is blue.</p>
```

## ចំណុចសំខាន់

- Attribute ផ្តល់ព័ត៌មានបន្ថែមដល់ element។
- Attribute ត្រូវសរសេរក្នុង opening tag។
- Attribute ភាគច្រើនមានទម្រង់ `name="value"`។
