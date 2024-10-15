<script>
    import Icon from "@iconify/svelte";
</script>
<div class="ml-6 bg-container w-full rounded-[10px] border-[var(--grayish)] border">

    <div class="text-center mt-[5vh]">
        <Icon class="m-auto text-[100px] opacity-30" icon='solar:cloudy-moon-bold'/>
        <div class="mt-[2vh] font-semibold">
            Awaiting for content
        </div>
        <div class="mb-[5vh] mt-1">Nothing was added.. yet</div>
    </div>

</div>

<style>
    .bg-container {
        background-color: var(--sec);
        padding: 10px;
    }

    @media screen and (max-width: 600px) {
        .bg-container {
            margin-left: 0px !important;
        }
	}
</style>