<script>
	// Decoration Elements
	import Plop from '$lib/assets/img/items/plop.svg';
	import Uwu from '$lib/assets/img/items/uwu.svg';
	import Heart from '$lib/assets/img/items/heart.svg';
	import Profile from '$lib/assets/img/profile.png';
	import Pawsss from '$lib/assets/img/items/pawsssssss.svg';

	// Icons
	import CodePaint from '$lib/assets/img/icons/codepaint.svg';

	// Other Modules
	import Marqueeck from '@arisbh/marqueeck';
	import Icon from '@iconify/svelte';
</script>

<div class="headerPrim m-auto">
	<div class="flex mt-[20vh] mbIcn items-center">
		<img class="uw-icon1 w-[130px]" src={sucking yk what} alt="" />
		<div class="awaa-block ml-auto">:3</div>
	</div>
	<div class="text-[100px] mt-[-10px] headerCont text-center font-semibold">
		ello!
		<div class="relative inline-block">
			<img class="absolute top-[-30px] transform -translate-x-1/2" src={Plop} alt="" />
			<img class="absolute top-0 left-0 rounded-[20px]" src={Profile} alt="" />
			<img class="w-[100px]" src={Heart} alt="" />
		</div>
		name's <span class="text-[var(--pink)]">nova,</span>
		<div class="text-[70%] undertext mt-[-50px] relative">
			<span
				class="awaa-mb text-[var(--pink2)] text-[20px] absolute ml-[383px] mt-[13px] rotate-[-10deg] transform -translate-x-1/2"
				>&gt;~&lt;</span
			>
			i'm a web developer & designer!
		</div>
	</div>
	<div class="flex items-center">
		<div class="knot-block mt-3">alien classified as gay</div>
		<div class="pawssss ml-auto">
			<span class="hidden">love you platonically for the code leafus</span>
			<img src={Pawsss} alt="" />
		</div>
	</div>
</div>

<div
	class="aboutSec m-auto mt-[10vh] bg-[var(--sec)] p-4 rounded-[20px] border-[var(--grayish)] border"
>
	<div class="font-semibold flex gap-3 items-center text-[30px]">
		<img class="w-[50px]" src={CodePaint} alt="" />
		About Me
	</div>
	<div class="text-[18px] mt-3 desc">
	no about me yet because svelte wants me to kms fr
	</div>

	<div class="flex items-center gap-4 w-full">
		<div class="sepe h-[3px] w-full rounded-[10px]"></div>
		<Icon class="text-[50px] text-[var(--pink2)]" icon="solar:heart-bold" />
		<div class="sepe h-[3px] w-full rounded-[10px]"></div>
	</div>

	<div class="mt-1">
		<div class="grid grid-cols-2 technologies w-full gap-5">
			<div class="technologies-block w-full p-3 rounded-[10px] overflow-clip">
				<div class="flex items-center text-[25px] font-semibold">
					<div class="iconContainer mr-3">
						<Icon class="rotate-[-10deg]" icon="solar:palette-round-bold" />
					</div>
					Frontend
				</div>
				<div class="mt-3">
					I have the most experience in frontend development 4 years to be exact i've work with
					variety of different frameworks and libs.
				</div>
				<Marqueeck
					--marqueeck-padding-y="0.5rem"
					class="gap-[3rem] [--duration:20s] [--gap:3rem] mt-3"
				>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:svelte'/>
						Svelte
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:react-dark'/>
						React
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:nextjs-dark'/>
						NextJS
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:vuejs-dark'/>
						Vue3
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:nuxtjs-dark'/>
						Nuxt
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:css'/>
						CSS
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:html'/>
						HTML
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:tailwindcss-dark'/>
						TailwindCSS
					</div>
				</Marqueeck>
			</div>
			<div class="technologies-block mt-ma w-full p-3 rounded-[10px] overflow-clip">
				<div class="flex items-center text-[25px] font-semibold">
					<div class="iconContainer mr-3">
						<Icon class="rotate-[-10deg]" icon="solar:server-square-cloud-bold" />
					</div>
					Backend
				</div>
				<div class="mt-3">
					I have only 2-3 years of experience with backend but sill i've worked with multiple
					libraries frameworks to create various APIs.
				</div>
				<Marqueeck class="gap-[3rem] [--duration:20s] [--gap:3rem] mt-3" --marqueeck-padding-y="0.5rem">
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:golang'/>
						Golang
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:nodejs-dark'/>
						NodeJS
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:expressjs-dark'/>
						ExpressJS
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:bun-dark'/>
						Bun
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:mongodb'/>
						MongoDB
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:typescript'/>
						TypeScript
					</div>
					<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
						<Icon icon='skill-icons:javascript'/>
						JavaScript
					</div>
				</Marqueeck>
			</div>
		</div>
		<div class="technologies-block w-full p-3 rounded-[10px] overflow-clip mt-3">
			<div class="flex items-center text-[25px] font-semibold">
				<div class="iconContainer mr-3">
					<Icon class="rotate-[-10deg]" icon="mynaui:sparkles-solid" />
				</div>
				Other Technologies
			</div>
			<div class="mt-3">
				When it comes to creating applications i use variety of other technologies and services
			</div>
			<Marqueeck class="gap-[3rem] [--duration:20s] [--gap:3rem] mt-3" --marqueeck-padding-y="0.5rem">
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='skill-icons:cloudflare-dark'/>
					Cloudflare!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='skill-icons:linux-dark'/>
					Linux!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='skill-icons:npm-dark'/>
					NPM!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='skill-icons:vscode-dark'/>
					Visual Studio Code!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='skill-icons:git'/>
					Git!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon class="text-[#609926]" icon='pajamas:gitea'/>
					Gitea!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon icon='devicon:insomnia'/>
					Insomnia!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon class="text-[var(--pink3)]" icon='solar:server-square-cloud-bold'/>
					Selfhosting!
				</div>
				<div class="flex items-center gap-2 font-semibold bg-[var(--sec)] pl-3 pr-3 pt-1 pb-1 rounded-[10px]">
					<Icon class="text-[#394eff]" icon='simple-icons:spaceship'/>
					Spaceship!
				</div>
			</Marqueeck>
		</div>
	</div>
</div>

<style>
	.uw-icon1 {
		margin-left: 15%;
	}

	@media screen and (max-width: 1366px) {
		.uw-icon1 {
			margin-left: 5%;
		}

		.awaa-block {
			margin-right: 5% !important;
		}

		.knot-block {
			margin-left: 10% !important;
		}

		.pawssss {
			margin-right: 10% !important;
		}

		.aboutSec {
			max-width: 80% !important;
		}
	}

	@media screen and (max-width: 600px) {
		.headerCont {
			font-size: 90px;
		}

		.undertext {
			font-size: 50px;
			margin-top: auto !important;
		}

		.technologies {
			display: block !important;
		}

		.aboutSec {
			max-width: 100% !important;
		}

		.mt-ma {
			margin-top: 12px;
		}

		.mbIcn {
			margin-top: 10vh !important;
		}

		.awaa-mb {
			display: none;
		}
	}

	.awaa-block {
		background: rgba(244, 120, 140, 0.26);
		height: 60px;
		width: 60px;
		border-radius: 15px;
		display: flex;
		align-items: center;
		justify-content: center;
		color: var(--pink2);
		font-weight: 600;
		font-size: 35px;
		margin-right: 15%;
		rotate: 20deg;
	}

	.knot-block {
		background: rgba(244, 120, 140, 0.26);
		height: 40px;
		width: 300px;
		border-radius: 15px;
		display: flex;
		align-items: center;
		justify-content: center;
		color: var(--pink2);
		font-weight: 600;
		font-size: 20px;
		margin-left: 20.4%;
		rotate: -4deg;
	}

	.pawssss {
		margin-right: 20%;
	}

	.iconContainer {
		background: rgba(244, 120, 140, 0.26);
		height: 50px;
		width: 50px;
		display: flex;
		align-items: center;
		justify-content: center;
		border-radius: 15px;
		font-size: 25px;
		color: var(--pink2);
	}

	/* .pb-seperator {
		background: rgb(234,73,103);
		background: linear-gradient(90deg, rgba(234,73,103,1) 0%, rgba(13,13,13,1) 78%);
		height: 10px;
		width: 100%;
		border-radius: 10px;
	} */

	.desc a {
		color: var(--pink2);
		font-weight: 600;
		transition: 300ms;
	}

	.desc a:hover {
		color: var(--pink);
		transition: 300ms;
	}

	.aboutSec {
		max-width: 70%;
	}

	.technologies-block {
		background-color: var(--bg);
		border: 1px solid var(--grayish);
	}

	.sepe {
		background-color: var(--pink);
	}
</style>
