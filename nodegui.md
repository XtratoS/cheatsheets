### view with grid layout
```ts
const view = new QWidget();
const layout = new QGridLayout();
view.setLayout(layout);
```
### column stretch relatively
```ts
layout.setColumnStretch(colNum, colStretch);
```
### adding widgets to the rows and columns of grid layout
```ts
layout.addWidget(widget: Widget, rowNum: number, colNum: number);
```
### align text in center of label
```css
{
  qproperty-alignment: AlignCenter;
}
```
