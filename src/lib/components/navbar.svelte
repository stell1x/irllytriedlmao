<script>
	import Logo from '$lib/assets/img/Logo.svg';
    import NtLogo from '$lib/assets/img/ntLogo.svg'
    import Icon from '@iconify/svelte'
    import { page } from '$app/stores';
</script>

<div class="flex iems-center mt-[5vh]">
	<div class="transition-all active:scale-90 p-logo">
		<a href="/"><img src={Logo} alt="" /></a>
	</div>
    <div class="transition-all active:scale-90 m-logo">
		<a href="/"><img class="w-[25px]" src={NtLogo} alt="" /></a>
	</div>
	<div class="ml-auto gap-2 flex items-center">
		<a class="transition-all active:scale-90" href="/projects">
			<div class:nv-active={$page.url.pathname.startsWith('/projects')} class="nv-button flex items-center gap-2"><Icon icon='solar:code-linear'/> Projects</div>
		</a>
		<a class="transition-all active:scale-90" href="/services">
			<div class:nv-active={$page.url.pathname.startsWith('/services')} class="nv-button flex items-center gap-2"><Icon icon='solar:widget-3-bold'/> Services</div>
		</a>
	</div>
</div>

<style>
    .nv-button {
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 5px;
        padding-bottom: 5px;
        border-radius: 10px;
        color: var(--pink2);
        font-weight: 600;
        transition: 300ms;
    }

    .nv-button:hover {
        background: rgba(244, 120, 140, 0.26);
        transition: 300ms;
    }

    .nv-active {
        background: rgba(244, 120, 140, 0.26);
    }

    .m-logo {
        display: none;
    }

    @media screen and (max-width: 600px) {
        .p-logo {
            display: none;
        }

        .m-logo {
            display: block;
        }
	}
</style>
