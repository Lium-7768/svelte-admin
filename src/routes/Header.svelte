<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	import github from '$lib/images/github.svg';
</script>

<header>
	<div class="corner">
		<a href="https://kit.svelte.dev">
			<img src={logo} alt="SvelteKit" />
		</a>
	</div>

	<nav>
		<ul>
			<li>
				<a href="https://kit.svelte.dev">
					<img src={logo} alt="SvelteKit" />
				</a>
			</li>
		</ul>
	</nav>
</header>

<style lang="less">
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
		a {
			display: flex;
			align-items: center;
			justify-content: center;
			width: 100%;
			height: 100%;
		}

		img {
			width: 2em;
			height: 2em;
			object-fit: contain;
		}
	}

	nav {
		ul {
			list-style: none;
			li {
				img {
					width: 2em;
					height: 2em;
					object-fit: contain;
				}
			}
		}
	}
</style>
