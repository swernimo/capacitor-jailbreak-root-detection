# @meedika/capacitor-jailbreak-root-detection

This is a Capacitor 6 Jailbreak Root detection plugin.

## Install

```bash
npm install @meedika/capacitor-jailbreak-root-detection
npx cap sync
```

## API

<docgen-index>

* [`isJailbrokenOrRooted()`](#isjailbrokenorrooted)
* [`isSimulator()`](#issimulator)
* [`isDebuggedMode()`](#isdebuggedmode)
* [`exitApp()`](#exitapp)
* [Interfaces](#interfaces)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### isJailbrokenOrRooted()

```typescript
isJailbrokenOrRooted() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### isSimulator()

```typescript
isSimulator() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### isDebuggedMode()

```typescript
isDebuggedMode() => Promise<JailbreakRootResult>
```

**Returns:** <code>Promise&lt;<a href="#jailbreakrootresult">JailbreakRootResult</a>&gt;</code>

--------------------


### exitApp()

```typescript
exitApp() => void
```

--------------------


### Interfaces


#### JailbreakRootResult

| Prop         | Type                 |
| ------------ | -------------------- |
| **`result`** | <code>boolean</code> |

</docgen-api>
