0.3.2.2
=======

  * Supported `xml-conduit-1.4` and `lens-4.15`

0.3.2.1
=======

  * Put missing files in the source distribution

0.3.2.0
=======

  * Add `texts`

0.3.1.0
=======

  * Re-export `ParseSettings` and `RenderSettings`

0.3.0.0
=======

  * Helpers to render values of `Element` type

  * Complete set of isos/prisms for types in Text.XML

  * `attr` is now a Lens, not a Traversal, so it can add and remove attributes from the node

  * `Ixed` instance for `Element` traverses child `Element`s instead of attributes

  * Avoid working with `def` directly, instead take settings endomorphisms as arguments in `*With` functions

  * Add `ixOf` to aid indexing subnodes chosen by a `Traversal`

0.2.0.0
=======

  * Update to `lens-4.0`

0.1.0.1
=======

  * _Maintenance_: Upper bound on `lens`

0.1.0.0
=======

  * Initial release
