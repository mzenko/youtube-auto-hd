<script lang="ts">
  import { getI18n } from "~shared-scripts/ythd-utils";

  const i18n: { [key: string]: string } = {
    labelSubheader: getI18n("cj_i18n_06860", "Support developer")
  };
</script>

<footer class="mt-5">
  <div>{i18n.labelSubheader}</div>
</footer>

