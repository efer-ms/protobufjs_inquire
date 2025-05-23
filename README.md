efer-ms_protobufjs_inquire_no_eval
===================
This is a fork of @protobufjs/inquire withou eval(). It is intended to
be used as an override in dependent packages.

@protobufjs/inquire
===================
[![npm](https://img.shields.io/npm/v/@protobufjs/inquire.svg)](https://www.npmjs.com/package/@protobufjs/inquire)

Requires a module only if available and hides the require call from bundlers.

API
---

* **inquire(moduleName: `string`): `?Object`**<br />
  Requires a module only if available.

**License:** [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
