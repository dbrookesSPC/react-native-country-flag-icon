# react-native-country-flag-icon

This is a React-Native package to display every 254 Country flags with the [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) Standard!

Credit to the original author of this package, I just forked to make them smaller: https://github.com/YannisHofmann/react-native-country-flag

[![NPM](https://img.shields.io/npm/v/react-native-country-flag-icon.svg)](https://www.npmjs.com/package/react-native-country-flag-icon)

## Install

```bash
npm install --save react-native-country-flag-icon
```

## Usage

This is a simple example how you can use the `CountryFlag` component.

```jsx
import CountryFlag from "react-native-country-flag-icon";

<CountryFlag isoCode="de" size={25} />
```

You can only use the [ISO 3166-1 alpha-2 Standard](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) for the isoCode property.

## Props

| Prop    |       Type        |                                                    Desciption                                                    |
| ------- | :---------------: | :--------------------------------------------------------------------------------------------------------------: |
| isoCode |      String       | Define the country flag with the [ISO 3166-1 alpha-2 Standard](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2). |
| size    |      Integer      |Define the size from the country flag.                                            |
| style   |    Stylesheet     |Customize the style from the `CountryFlag` component.                             |                              

## License

MIT © [David Brookes](https://github.com/dbrookesSPC)
