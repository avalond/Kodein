[com.github.salomonbrys.kodein.conf](../index.md) / [KodeinGlobalAware](.)

# KodeinGlobalAware

`interface KodeinGlobalAware : `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)

A `KodeinAware` class that needs no implementation because the kodein used will be the [global](../global.md) One True Kodein.

### Properties

| Name | Summary |
|---|---|
| [kodein](kodein.md) | `open val kodein: `[`Kodein`](../../com.github.salomonbrys.kodein/-kodein/index.md)<br>The global One True Kodein. |

### Extension Properties

| Name | Summary |
|---|---|
| [lazy](../../com.github.salomonbrys.kodein/lazy.md) | `val `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.lazy: `[`LazyKodein`](../../com.github.salomonbrys.kodein/-lazy-kodein/index.md)<br>Allows lazy retrieval from a [Kodein](../../com.github.salomonbrys.kodein/-kodein/index.md) or [KodeinAware](../../com.github.salomonbrys.kodein/-kodein-aware.md) object. |

### Extension Functions

| Name | Summary |
|---|---|
| [With](../../com.github.salomonbrys.kodein/-with.md) | `fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.With(argType: `[`TypeToken`](../../com.github.salomonbrys.kodein/-type-token/index.md)`<A>, arg: A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>Allows to get a provider or an instance from a curried factory with an `A` argument. |
| [WithF](../../com.github.salomonbrys.kodein/-with-f.md) | `fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.WithF(argType: `[`TypeToken`](../../com.github.salomonbrys.kodein/-type-token/index.md)`<A>, arg: () -> A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>Allows to get a provider or an instance from a curried factory with an `A` argument. |
| [newInstance](../../com.github.salomonbrys.kodein/new-instance.md) | `fun <T> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.newInstance(creator: `[`Kodein`](../../com.github.salomonbrys.kodein/-kodein/index.md)`.() -> T): T`<br>Allows to create a new instance of an unbound object with the same API as when bounding one. |
| [with](../../com.github.salomonbrys.kodein/with.md) | `fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.with(arg: () -> A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>`fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.with(arg: A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>Allows to get a provider or an instance from a curried factory with an `A` argument. |
| [with](../../com.github.salomonbrys.kodein.erased/with.md) | `fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.with(arg: () -> A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>`fun <A> `[`KodeinAwareBase`](../../com.github.salomonbrys.kodein/-kodein-aware-base/index.md)`.with(arg: A): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<A>`<br>Allows to get a provider or an instance from a curried factory with an `A` argument. |
| [withContext](../../com.github.salomonbrys.kodein.android/with-context.md) | `fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(ctx: Context): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(f: Fragment): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(f: Fragment): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(d: Dialog): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(v: View): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(tsa: AbstractThreadedSyncAdapter): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(l: Loader<*>): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>`fun `[`KodeinAware`](../../com.github.salomonbrys.kodein/-kodein-aware.md)`.withContext(l: Loader<*>): `[`CurriedKodeinFactory`](../../com.github.salomonbrys.kodein/-curried-kodein-factory/index.md)`<Context>`<br>Allows to get an instance or a provider from a factory which takes a `Context` as argument. |
