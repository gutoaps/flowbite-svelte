<script lang="ts">
	import classNames from 'classnames';
	export let divClass = 'inline-flex rounded-md shadow-sm';
</script>

<div {...$$restProps} class={classNames(divClass, $$props.class)} role="group">
	<slot />
</div>
