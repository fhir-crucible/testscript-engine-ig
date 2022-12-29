### Interpretation

If this extension is present on a [TestReport](StructureDefinition-testscript-engine-testreport.html) instance, then the `valueBoolean` element indicates whether the TestScript was executed as a subtest. If the extension is not present, then the TestScript was not executed as a subtest, same as if the extension was present with `valueBoolean = false`.