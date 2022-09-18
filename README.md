react-native-insta-pagination-dots
=============

Instagram Like dot pagination component for React Native 

## Installation

Installation can be done through `npm`:

npm
```shell
npm i react-native-insta-pagination-dots
```
yarn
```shell
yarn add react-native-insta-pagination-dots
```

-----
## Usage
You can easily add to your project.<br/>
just import component and set current page index and max page index.
```js
import React from 'react'
import {View} from 'react-native'
import PaginationDot from 'react-native-insta-pagination-dots'

const ExampleDotPaginate:React.FC = ()=>{
    const [curPage] = React.useState(0);
    
    return (
        <PaginationDot
            activeDotColor={'black'}
            curPage={curPage}
            maxPage={20}
        />
    )
}

export default ExampleDotPaginate;
```

-----
## Example

<img src="https://user-images.githubusercontent.com/4319422/189922878-7172d48c-8307-47ac-806a-6255f7bd6d3b.gif" alt="Pagination Dot Demo" width="320"/>

-----
## API

### Props

| **Prop**           | **Type**                    | **Required(Default Value)** | **Description**                                                |
|--------------------| ----------------------------|----------------------------|----------------------------------------------------------------|
| `curPage`          | `number`                    | required                   | Pagination curernt Page                                        |
| `maxPage`          | `number`                    | required                   | Total Page in Pagination                                       |
| `activeDotColor`   | `string`                    | required                   | Active Dot Color. dot will control by opacity                  |
| `inactiveDotColor` | `string`                    | undefined                  | InActive Dot Color. dot will control by opacity                |
| `sizeRatio`        | `number`                    | 1.0                        | Customize Dot Size. minimum value is 1.0 (*recommend 1.0 ~ 2.0*) |
| `vertical`         | `boolean`                   | false                      | Dot direction                                                  |

## Contributing


## License

MIT.

## Author

shubh
