# React-Customizable-Timeline

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blueviolet.svg?style=flat)](http://makeapullrequest.com) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat)](https://github.com/prettier/prettier) ![npm bundle size](https://img.shields.io/bundlephobia/minzip/gallereact.svg) [![Issues](http://img.shields.io/github/issues/yw3028/React-Customizable-Timeline.svg)](https://github.com/yw3028/React-Customizable-Timelin/issues )

## Getting Started
```bash
$ npm i react-customizable-timeline
```

### How to use
**Step 1:** Import the component
```js
import Timeline from 'react-customizable-timeline';
```
**Step 2:** Use it in your amazing application! For example:
```typescript jsx
<Timeline
  data={data}
  primaryDarkColor='black'
  primaryLightColor='white'
  titleShape='circlr'
  dotShape='diamond'
  lineStyle='dotted
  primaryFont='monospace'
  animation={true}
/>
```

## Configuration
### Data

*Data is an array of objects. For example:*

```typescript jsx
const data = [
  {
      title: 'TITLE 1',
      events: [
          {
            title: 'EVENT TITLE',
            subtitle: 'EVENT SUBTITLE',
            content:'CONTENT',
            location: 'LOCATION',
            label: '#LABLE1 #LABLE2',
            img: {
                url:
                    'https://images.unsplash.com/photo-1600790078201-5490baf711d6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60',
                alt: 'pic',
               },
          }]
    },
    ]
```

> Please note that besides `events[title]`, everything is optional!

 
### Component Settings
|      **Property**     | **Type** | **Required** |     **Default**     |                **Options**                |
|:---------------------:|:--------:|:------------:|:-------------------:|:-----------------------------------------:|
|     **animation**     |  Boolean |   Optional   |         true        |                 true/false                |
|  **primaryDarkColor** |  String  |   Optional   |       #625261       |                                           |
| **primaryLightColor** |  String  |   Optional   |       #F5F5DC       |                                           |
|    **primaryFont**    |  String  |   Optional   | 'Chivo', sans-serif |                                           |
|     **titleShape**    |  String  |   Optional   |        circle       | `circle`/`square`/`rectangular`/`diamond` |
|      **dotShape**     |  String  |   Optional   |        circle       |     `circle`/`square`/`line`/`diamond`    |
|     **lineStyle**     |  String  |   Optional   |        dotted       |     `solid`/`dotted`/`dashed`/`hidden`    |








