<script lang="ts">
  import { FeatureSettings as McpServerInstallSettings } from "src/features/mcp-server-install";
  import type McpServerPlugin from "src/main";

  export let plugin: McpServerPlugin;
</script>

<div class="settings-container">
  <McpServerInstallSettings {plugin} />
</div>
