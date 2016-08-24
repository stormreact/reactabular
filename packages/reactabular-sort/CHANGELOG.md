2.0.0 / 2016-08-16
==================

  * Breaking - Return sorting columns if no selected column is passed.
  * Breaking - Extract header styling to a separate file (`style.css` at package root) and allow `style` prop to be passed.
  * Breaking - Port sorting to a property based scheme over index one.
  * Improvement - Mark React as a peer dependency.
  * Improvement - Allow sorting `fieldName` to be customized for `sort`, `header`, and `reset`. This is useful if you want to sort per `property` for example.
  * Improvement - Allow `sorter` `getColumns` mechanism to be customized. This is needed to make `fieldName` useful.

1.1.4 / 2016-08-04
==================

  * Bug fix - Do not crash if column `cell` definition is missing. #178

1.0.11 / 2016-07-29
===================

  * Bug fix - `sort.reset` accepts object properly now. Earlier it bailed out too early.

1.0.10 / 2016-07-29
===================

  * Improvement - `sort.sort` accepts `event` parameter now. It defaults to `onClick`.
  * Improvement - `sort.reset` is a new transform that can be used to remove the given column from the sorting rules.
  * Improvement - `sort.header` is a new formatter that can be used to apply sorting. This is handy if you use `sort.reset`.

1.0.0 / 2016-07-25
==================

  * Initial release.