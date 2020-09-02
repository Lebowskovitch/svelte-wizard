# Usage

```
<script>
  import TestPage from "./TestPage.svelte";
  import { Wizard, WizardPage } from "svelte-wizard";
</script>

<style>

</style>

<main>
  <Wizard>
    <WizardPage>
      <TestPage />
    </WizardPage>
    <WizardPage>
      <TestPage foo="baz" />
    </WizardPage>
    <WizardPage>
      <TestPage foo="test" />
    </WizardPage>
    <WizardPage>
      <TestPage foo="another" />
    </WizardPage>
  </Wizard>
</main>
```