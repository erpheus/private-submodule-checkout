# private-submodule-checkout
Checkout private submodules by providing a deployment key to them

Usage

```yaml
- uses: erpheus/private-submodule-checkout@v1
  with:
    deployment_key: ${{ secrets.YOUR_DEPLOYMENT_KEY }}
```

Thanks to [this post](https://rgoswami.me/posts/priv-gh-actions/) by [Rohit Goswami](https://github.com/HaoZeke/).
