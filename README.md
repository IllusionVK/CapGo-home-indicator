# @capgo/home-indicator
  <a href="https://capgo.app/"><img src='https://raw.githubusercontent.com/Cap-go/capgo/main/assets/capgo_banner.png' alt='Capgo - Instant updates for capacitor'/></a>
  
<div align="center">
<h2><a href="https://capgo.app/">Check out: Capgo — live updates for capacitor</a></h2>
</div>

hide and show home button indicator in Capacitor app

## Install

```bash
npm install @capgo/home-indicator
npx cap sync
```

## API

<docgen-index>

* [`hide()`](#hide)
* [`show()`](#show)
* [`isHidden()`](#ishidden)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### hide()

```typescript
hide() => Promise<void>
```

Hide the home indicator.

**Since:** 0.0.1

--------------------


### show()

```typescript
show() => Promise<void>
```

Show the home indicator.

**Since:** 0.0.1

--------------------


### isHidden()

```typescript
isHidden() => Promise<{ hidden: boolean; }>
```

Get the home indicator status.

**Returns:** <code>Promise&lt;{ hidden: boolean; }&gt;</code>

**Since:** 0.0.1

--------------------

</docgen-api>

### CSS Variables

You can use `--safe-area-inset-bottom` to make sure your content is not hidden by the home indicator
This variable is injected by the plugin for android.
It's useful if you set real fullscreen mode on android.
with :
```java
getWindow().setDecorFitsSystemWindows(false);
```


# Credits

This plugin was created originally for [Kick.com](https://kick.com) by [Capgo](https://capgo.app)
