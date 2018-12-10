
Running:
```
$ now
```

Results in:
```
12/10 08:25 PM (16m)
ModuleDependencyError: Can't reexport the named export 'BREAK' from non EcmaScript module (only default export is available)
    at Compilation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1368:21)
    at Compilation.finish (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1165:9)
    at hooks.make.callAsync.err (/tmp/38472471/node_modules/webpack/lib/Compiler.js:544:17)
    at _err0 (eval at create (/tmp/38472471/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:11:1)
    at Promise.all.then (/tmp/38472471/node_modules/webpack/lib/DynamicEntryPlugin.js:74:20)
    at <anonymous>
    at process._tickCallback (internal/process/next_tick.js:188:7)
    at HarmonyExportImportedSpecifierDependency._getErrors (/tmp/38472471/node_modules/webpack/lib/dependencies/HarmonyExportImportedSpecifierDependency.js:360:6)
    at HarmonyExportImportedSpecifierDependency.getErrors (/tmp/38472471/node_modules/webpack/lib/dependencies/HarmonyExportImportedSpecifierDepe
12/10 08:25 PM (16m)
ack/lib/Compiler.js:544:17)
    at _err0 (eval at create (/tmp/38472471/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:11:1)
    at Promise.all.then (/tmp/38472471/node_modules/webpack/lib/DynamicEntryPlugin.js:74:20)
    at <anonymous>
    at process._tickCallback (internal/process/next_tick.js:188:7) ModuleDependencyError: Can't reexport the named export 'SchemaMetaFieldDef' from non EcmaScript module (only default export is available)
    at Compilation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1368:21)
    at Compilation.finish (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1165:9)
    at hooks.make.callAsync.err (/tmp/38472471/node_modules/webpack/lib/Compiler.js:544:17)
    at _err0 (eval at create (/tmp/38472471/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:11:1)
    at Promise.all.then (/tmp/38472471/node_modules/webpack/lib/DynamicEntryPlugin.js:74:20)
    at <anonymous>
    at process._tickCallback (internal/pr
12/10 08:25 PM (16m)
lation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1363:22)
    at Compilation.finish (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1165:9)
    at hooks.make.callAsync.err (/tmp/38472471/node_modules/webpack/lib/Compiler.js:544:17)
    at _err0 (eval at create (/tmp/38472471/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:11:1)
    at Promise.all.then (/tmp/38472471/node_modules/webpack/lib/DynamicEntryPlugin.js:74:20)
    at <anonymous>
    at process._tickCallback (internal/process/next_tick.js:188:7) ModuleDependencyError: Can't reexport the named export 'assertType' from non EcmaScript module (only default export is available)
    at Compilation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1368:21)
    at Compilation.finish (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1165:9)
    at hooks.make.callAsync.err (/tmp/38472471/node_modules/webpack/lib/Compiler.js:544:17)
    at _err0 (eva
12/10 08:25 PM (16m)
 HarmonyExportImportedSpecifierDependency.getErrors (/tmp/38472471/node_modules/webpack/lib/dependencies/HarmonyExportImportedSpecifierDependency.js:338:16)
    at Compilation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1363:22)
    at Compilation.finish (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1165:9)
    at hooks.make.callAsync.err (/tmp/38472471/node_modules/webpack/lib/Compiler.js:544:17)
    at _err0 (eval at create (/tmp/38472471/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:11:1)
    at Promise.all.then (/tmp/38472471/node_modules/webpack/lib/DynamicEntryPlugin.js:74:20)
    at <anonymous>
    at process._tickCallback (internal/process/next_tick.js:188:7) ModuleDependencyError: Can't reexport the named export 'isExecutableDefinitionNode' from non EcmaScript module (only default export is available)
    at Compilation.reportDependencyErrorsAndWarnings (/tmp/38472471/node_modules/webpack/lib/Compilation.js:1368:21)
    at Compil
12/10 08:25 PM (16m)
error Command failed with exit code 1.
```

Commenting out `import 'apollo-boost';` and it'll depoy without issues.