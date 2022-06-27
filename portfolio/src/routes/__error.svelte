<script context="module">
	// @ts-ignore
	export function load({ error }) {
		return {
			props: { message: error.message }
		};
	}
</script>

<script lang="ts">
  export let message: string
</script>

<div>
  <h1>oops</h1>
  <p>{message}</p>
</div>
