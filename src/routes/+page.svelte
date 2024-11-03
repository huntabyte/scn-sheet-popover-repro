<script lang="ts">
	import * as Sheet from '$lib/components/ui/sheet/index.js';
	import * as Popover from '$lib/components/ui/popover/index.js';
</script>

<Sheet.Root>
	<Sheet.Trigger>Click to open sheet</Sheet.Trigger>
	<Sheet.Content side="right">
		<Popover.Root>
			<Popover.Trigger>Click to open popover</Popover.Trigger>
			<Popover.Content class="w-80">
				<div>After opening the popover the sheet is not closing by outside clicks anymore.</div>
			</Popover.Content>
		</Popover.Root>
	</Sheet.Content>
</Sheet.Root>
