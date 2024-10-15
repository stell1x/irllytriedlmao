<script>
    import Server from '$lib/assets/img/icons/server.svg'
    import Icon from '@iconify/svelte'
</script>

<div class="mt-6">
    <div class="flex items-center font-semibold text-[25px] gap-5">
        <img class="w-[60px]" src={Server} alt="">
        My Selfhosted Services
    </div>

    <div class="list mt-6">
        <a href="https://git.fluffy.pw" target="_blank">
            <div class="flex items-center item gitea transition-all duration-300">
                <div class="appIcon flex items-center justify-center rounded-[10px] text-[20px]">
                    <Icon class="text-[#609926]" icon='pajamas:gitea'/>
                </div>
                <div class="ml-3">
                    <div class="font-semibold">Gitea</div>
                    <div>Lightweight selfhosted github alternative written in Go</div>
                </div>
            </div>
        </a>
    </div>
</div>

<style>
    .list {
        background-color: var(--sec);
        border: 1px solid var(--grayish);
        padding: 10px;
        border-radius: 15px;
    }

    .appIcon {
        background-color: rgba(141, 201, 81, 0.3);
        width: 40px;
        height: 40px;
    }

    .item {
        padding-left: 10px;
        padding-top: 5px;
        padding-bottom: 5px;
        border-radius: 10px;
    }

    .gitea:hover {
        background-color: rgba(141, 201, 81, 0.3);
    }
</style>