# Image Card

Customize a card with image by 2 type: fill or transparent

<img src="https://raw.githubusercontent.com/zeref278/image_card/main/example/demo.gif"/>

## Usage
### Fill image card

<img src="https://raw.githubusercontent.com/zeref278/image_card/main/example/screenshot.png" width="300"/>

```dart
FillImageCard(
  width: 200,
  heightImage: 140,
  imageProvider: AssetImage('assets/mockup.png'),
  tags: [_tag('Category', () {}), _tag('Product', () {})],
  title: _title(),
  description: _content(),
),
```

### Transparent image card

<img src="https://raw.githubusercontent.com/zeref278/image_card/main/example/screenshot1.png" width="300"/>

```dart
TransparentImageCard(
  width: 200,
  imageProvider: AssetImage('assets/mockup.png'),
  tags: [ _tag('Product', () {}), ],
  title: _title(color: Colors.white),
  description: _content(color: Colors.white),
),
```

## Parameter

You can see parameter detail in github repo.
