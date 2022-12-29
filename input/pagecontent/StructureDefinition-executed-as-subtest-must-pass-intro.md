### Interpretation

If this extension is present on a [TestReport](StructureDefinition-testscript-engine-testreport.html) instance, then the `valueBoolean` element indicates whether the TestScript was required to pass for the calling assertion to pass. If the extension is not present, then the TestScript was required to pass, same as if the extension was present with `valueBoolean = true`.