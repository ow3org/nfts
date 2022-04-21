# NFT Elements

The easiest way to integrate NFTs into your application.

## 🐙 Features

This cross-framework (React, Vue, Svelte, Angular, etc.) component library is compatible for the following features:

- `<nft />`
- `<collection />`
- `<launch-pad />`
- `<nft-staking />`

Read more about these features in their respective [docs](https://meema.xyz/docs).

## 💡 Usage

It's incredibly easy to use a Web Components within your own project. Check out the `index.html` to get an idea how it can be done.

```html
<!-- the following element props is required to be set to render your NFT -->
<collection candy-machine-id="CMhtpchN7u1EQuGQRwvEbpGYqVZ9338mdzyLeJdido1t"></collection>
<nft mint-address="7A6cbN1WzUvXoXpam32Dj3JoVbGXPyRZqjRpheDsTD2q" />
<launch-pad />
<nft-staking />

<!-- optional props -->
<nft mint-address="..." width="400" />

...
```

## 🖥️ Browsers

Meema Elements is built for the modern web and avoids bloated polyfills and outdated environments as much as possible. Currently, it supports all browsers that fully implement the [Custom Elements V1][caniuse-custom-el-v1].

- Edge 79+
- Firefox 63+
- Chrome 67+
- Safari 13.1+
- Opera 64+
- iOS Safari 13.7+
- Android Browser 81+
- Opera Mobile 59+
- Chrome for Android 88+

[caniuse-custom-el-v1]: https://caniuse.com/custom-elementsv1

## 🧪 Testing

```bash
yarn test
```

## 📈 Changelog

Please see our [releases](https://github.com/meemalabs/nft-elements/releases) page for more information on what has changed recently.

## 💪🏼 Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## 🏝 Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[NFT Elements on GitHub](https://github.com/meemalabs/nft-elements/discussions)

For casual chit-chat with others using this package:

[Join the Meema Discord Server](https://discord.meema.io)

## 📄 License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.

Made with ❤️ by Meema, Inc.
