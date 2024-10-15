<script>
    import Icon from '@iconify/svelte'
    import { page } from '$app/stores';
</script>

<div class="prSb h-[102px]">
	<a href="/projects/fluffychat">
		<div class:item-active={$page.url.pathname === '/projects/fluffychat'} class="mb-2 transition-all active:scale-90 item flex items-center gap-2 font-semibold"><Icon icon='solar:code-linear'/> Fluffy Chat</div>
	</a>
    <a href="/projects/drive">
		<div class:item-active={$page.url.pathname === '/projects/drive'} class="transition-all active:scale-90 item flex items-center gap-2 font-semibold"><Icon icon='solar:code-linear'/> Leafus Drive</div>
	</a>
</div>

<style>
    .prSb {
        background-color: var(--sec);
        padding: 10px;
        border-radius: 10px;
        border: 1px solid var(--grayish);
        width: 200px;
    }

    .item {
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 6px;
        padding-bottom: 6px;
        border-radius: 10px;
        transition: 300ms;
        color: var(--pink2);
    }

    .item:hover {
        background: rgba(244, 120, 140, 0.26);
        transition: 300ms;
    }

    .item-active {
        background: rgba(244, 120, 140, 0.26);
    }

    @media screen and (max-width: 600px) {
        .prSb {
            width: 100% !important;
            margin-bottom: 10px;
        }
	}
</style>
