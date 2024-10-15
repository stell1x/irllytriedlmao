<script>
    import Icon from '@iconify/svelte'
</script>

<div class="ml-6 bg-container w-full rounded-[10px] border-[var(--grayish)] border">
    <div class="projectOverwiew p-5">
        <div class="text-[25px] font-semibold gap-5 flex items-center mb-3">
            <div class="h-[50px] w-[50px] projIcon flex items-center justify-center text-[30px] text-[var(--pink2)]">
                <Icon icon='solar:code-linear'/>
            </div>
            Project Info
        </div>
        <div class="text-[18px]">Name: Fluffy Chat</div>
        <div class="text-[18px]">Status: Active</div>
    </div>

    <div class="mt-5 ml-5">
        <img class="w-[250px]" src="https://media.leafus.wtf/storage/assets/fluffy-logo.svg" alt="">
        <div class="mt-2 text-[17px] font-semibold">
            FluffyChat the full-stack discord clone
        </div>

        <div class="text-[20px] font-semibold mt-2">
            Overview
        </div>

        <div class="mt-2">
            This project started after i was annoyed at how badly discord works so i decided to try and create a full-stack discord clone with its own api's etc
            storage solutions, account systems basically everything done from scratch right now its done in like 30% here is the list of things that are done and not done

            <div class="mt-3 mb-3 text-[20px] font-semibold">
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--green)]" icon='solar:check-square-bold'/>
                    Accounts - 100%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--yellow)]" icon='solar:question-square-bold'/>
                    Spaces - 20%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--pink3)]" icon='solar:close-square-bold'/>
                    DMs - 0%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--green)]" icon='solar:check-square-bold'/>
                    CDN - 100%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--pink3)]" icon='solar:close-square-bold'/>
                    Space Discovery - 0%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--yellow)]" icon='solar:question-square-bold'/>
                    User Settings - 10%
                </div>
                <div class="flex items-center gap-2">
                    <Icon class="text-[var(--yellow)]" icon='solar:question-square-bold'/>
                    Overall messaging system - Half works
                </div>
            </div>

            So in this project the "Guilds" are called "Spaces" [very original ik] for now i don't know what to say more i will add screenshots of the app in the future :3
        </div>
    </div>
</div>

<style>
    .bg-container {
        background-color: var(--sec);
        padding: 10px;
    }

    .projectOverwiew {
        background-color: var(--bg);
        border-radius: 10px;
        border: 1px solid var(--grayish);
    }

    .projIcon {
        background: rgba(244, 120, 140, 0.26);
        border-radius: 15px;
    }

    @media screen and (max-width: 600px) {
        .bg-container {
            margin-left: 0px !important;
        }
	}
</style>