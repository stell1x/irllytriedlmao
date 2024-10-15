<script>
	import Logo from '$lib/assets/img/Logo.svg';
	import Icon from '@iconify/svelte';
</script>

<div class="bg-[var(--sec)] footer flex mt-5 mb-5 p-5 rounded-[15px] border-[var(--grayish)] border">
	<div>
		<img src={Logo} alt="" />
		<div class="mt-3 font-semibold">
			This website is Opensource
			<div class="flex items-center gap-1">
				Created with <Icon class="text-[var(--pink2)]" icon="solar:heart-bold" /> in
				<span class="text-[#f86642]"><a href="https://svelte.dev" target="_blank">Svelte</a></span>
				by <span class="text-[var(--pink2)]">Leafus</span>
			</div>
		</div>
		<a href="https://git.fluffy.pw/leafus/leafus-wtf-rebuild" target="_blank">
			<button class="mt-3 srcBtn transition-all active:scale-90">Get Source</button>
		</a>
	</div>
	<div class="ml-auto w-[400px]">
		<div class="text-[var(--pink2)] text-[20px] font-semibold">Leafus.wtf</div>
		<div class="footerTxmb">
			This website is licensed under the MIT License. You're free to copy, distribute, edit the
			source code ;3
		</div>

        <div class="footerTextMb">
			This website is licensed under the <br>
            MIT License. You're free to copy <br>
            , distribute, edit the
			source code ;3
		</div>
		<div class="mt-3 opacity-50">© 2024 - Leafus.wtf</div>
	</div>
</div>

<style>
	@media screen and (max-width: 600px) {
        .footer {
            display: block !important;
        }

        .footerTxmb {
            display: none;
        }

        .footerTextMb {
            display: block !important;
        }
	}

    .footerTextMb {
        display: none;
    }

	.srcBtn {
		background: rgba(244, 120, 140, 0.26);
		padding-top: 5px;
		padding-bottom: 5px;
		padding-left: 10px;
		padding-right: 10px;
		border-radius: 10px;
		color: var(--pink2);
		font-weight: 600;
	}

	.srcBtn:hover {
		background-color: var(--pink2);
		color: black;
	}
</style>
