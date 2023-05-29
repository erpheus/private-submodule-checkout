# private-submodule-checkout
Checkout private submodules by providing a deployment key to them

Usage

```yaml
- uses: MikasaEureka/pub-private-submodule-checkout
  with:
    deployment_key: ${{ secrets.YOUR_DEPLOYMENT_KEY }}
or
- uses: MikasaEureka/pub-private-submodule-checkout
```

Thanks to [this post](https://rgoswami.me/posts/priv-gh-actions/) by [Rohit Goswami](https://github.com/HaoZeke/).
