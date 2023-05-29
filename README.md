# private-submodule-checkout
Checkout private submodules by providing a deployment key to them

Usage

```yaml
- uses: MikasaEureka/pub-private-submodule-checkout
  with:
    deployment_key: ${{ secrets.YOUR_DEPLOYMENT_KEY }}
    repo_pub: false
or
- uses: MikasaEureka/pub-private-submodule-checkout
  with:
    repo_pub: true
```

Thanks to [this post](https://rgoswami.me/posts/priv-gh-actions/) by [Rohit Goswami](https://github.com/HaoZeke/).  
and[this](https://github.com/releasehub-com/github-action-create-pr-parent-submodule)
still cant fix if key to switch case 
