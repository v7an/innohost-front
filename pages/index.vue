<template>
    <!--
    Author: Snowi (snw)
    Version: v0.1.0
    Url: Closed Source
    License(s): MIT
  -->
  <div class="bg-gray-900">
    <main>
      <!-- Hero section -->
      <div class="relative isolate overflow-hidden">
        <svg class="absolute inset-0 -z-10 h-full w-full stroke-white/10 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
          <defs>
            <pattern id="983e3e4c-de6d-4c3f-8d64-b9761d1534cc" width="200" height="200" x="50%" y="-1" patternUnits="userSpaceOnUse">
              <path d="M.5 200V.5H200" fill="none" />
            </pattern>
          </defs>
          <svg x="50%" y="-1" class="overflow-visible fill-gray-800/20">
            <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
          </svg>
          <rect width="100%" height="100%" stroke-width="0" fill="url(#983e3e4c-de6d-4c3f-8d64-b9761d1534cc)" />
        </svg>
        <div class="absolute left-[calc(50%-4rem)] top-10 -z-10 transform-gpu blur-3xl sm:left-[calc(50%-18rem)] lg:left-48 lg:top-[calc(50%-30rem)] xl:left-[calc(50%-24rem)]" aria-hidden="true">
          <div class="aspect-[1108/632] w-[69.25rem] bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-20" style="clip-path: polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)" />
        </div>
        <div class="mx-auto max-w-7xl px-6 pb-24 pt-10 sm:pb-40 lg:flex lg:px-8 lg:pt-40">
          <div class="mx-auto max-w-2xl flex-shrink-0 lg:mx-0 lg:max-w-xl lg:pt-8">
            <img data-aos="fade-down" class="h-11" src="https://cdn.discordapp.com/attachments/1229880919184117820/1235542070337339402/discotools-xyz-icon4.png?ex=6634bfb8&is=66336e38&hm=ad9f77bf2cfc92804faeb002c9b26eab6b82810c91720cf88cdab88d644dff34&" alt="innohost logo" />
            <div class="mt-24 sm:mt-32 lg:mt-16">
            </div>
            <h1 data-aos="fade-right" class="mt-10 text-4xl font-bold tracking-tight text-white sm:text-6xl">Vous êtes entre de bonnes mains avec InnoHost.</h1>
            <p data-aos="fade-right" class="mt-6 text-lg leading-8 text-gray-300">InnoHost propose un hébergement gratuit idéal pour vos bots Discord, qu'ils soient développés en Node.js ou en Python. Notre plateforme offre un environnement sécurisé et fiable pour exécuter vos bots, avec des performances optimales garanties.</p>
            <div data-aos="fade-right" class="mt-10 flex items-center gap-x-6">
              <a href="https://my.innohost.pro" class="rounded-md bg-white px-3.5 py-2.5 text-sm font-semibold text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Commencer</a>
              <a href="https://discord.gg/inno" class="text-sm font-semibold leading-6 text-white">Rejoignez notre discord <span aria-hidden="true">→</span></a>
            </div>
          </div>
          
        </div>
      </div>

      <!--
      <div class="mx-auto mt-8 max-w-7xl px-6 sm:mt-16 lg:px-8">
        <h2 class="text-center text-lg font-semibold leading-8 text-white">The world's best community are using our bot</h2>
        <div class="mx-auto mt-10 grid max-w-lg grid-cols-4 items-center gap-x-8 gap-y-10 sm:max-w-xl sm:grid-cols-6 sm:gap-x-10 lg:mx-0 lg:max-w-none lg:grid-cols-5">
          <img class="col-span-2 max-h-12 w-full object-contain lg:col-span-1" src="https://tailwindui.com/img/logos/158x48/transistor-logo-white.svg" alt="Transistor" width="158" height="48" />
          <img class="col-span-2 max-h-12 w-full object-contain lg:col-span-1" src="https://tailwindui.com/img/logos/158x48/reform-logo-white.svg" alt="Reform" width="158" height="48" />
          <img class="col-span-2 max-h-12 w-full object-contain lg:col-span-1" src="https://tailwindui.com/img/logos/158x48/tuple-logo-white.svg" alt="Tuple" width="158" height="48" />
          <img class="col-span-2 max-h-12 w-full object-contain sm:col-start-2 lg:col-span-1" src="https://tailwindui.com/img/logos/158x48/savvycal-logo-white.svg" alt="SavvyCal" width="158" height="48" />
          <img class="col-span-2 col-start-2 max-h-12 w-full object-contain sm:col-start-auto lg:col-span-1" src="https://tailwindui.com/img/logos/158x48/statamic-logo-white.svg" alt="Statamic" width="158" height="48" />
        </div>
      </div>
      -->

      <!-- Feature section -->
      <div class="mx-auto mt-32 max-w-7xl px-6 sm:mt-56 lg:px-8">
        <div class="mx-auto max-w-2xl text-center">
          <h2 data-aos="fade-down" class="text-base font-semibold leading-7 text-indigo-400">Inno-Host</h2>
          <p data-aos="fade-down" class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl">Votre serveur est entre de bonnes mains avec InnoHost.</p>
          <p data-aos="fade-down" class="mt-6 text-lg leading-8 text-gray-300">Avec Inno-Host, libérez le plein potentiel de vos bots Discord, en toute fiabilité et gratuitement.</p>
        </div>
        <div data-aos="fade-down" class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none">
          <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-3">
            <div v-for="feature in primaryFeatures" :key="feature.name" class="flex flex-col">
              <dt class="text-base font-semibold leading-7 text-white">
                <div class="mb-6 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-500">
                  <component :is="feature.icon" class="h-6 w-6 text-white" aria-hidden="true" />
                </div>
                {{ feature.name }}
              </dt>
              <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-300">
                <p class="flex-auto">{{ feature.description }}</p>
              </dd>
            </div>
          </dl>
        </div>
      </div>

      <!-- Feature section -->
      <div class="mt-32 sm:mt-56">
        <div class="mx-auto max-w-7xl px-6 lg:px-8">
        
        </div>

        <div data-aos="fade-up" class="mx-auto mt-16 max-w-7xl px-6 sm:mt-20 md:mt-24 lg:px-8">
          <dl class="mx-auto grid max-w-2xl grid-cols-1 gap-x-6 gap-y-10 text-base leading-7 text-gray-300 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-x-8 lg:gap-y-16">
            <div v-for="feature in secondaryFeatures" :key="feature.name" class="relative pl-9">
              <dt class="inline font-semibold text-white">
                <component :is="feature.icon" class="absolute left-1 top-1 h-5 w-5 text-indigo-500" aria-hidden="true" />
                {{ feature.name }}
              </dt>
              {{ ' ' }}
              <dd class="inline">{{ feature.description }}</dd>
            </div>
          </dl>
        </div>
      </div>

      <!-- CTA section -->
      <div data-aos="fade-down" class="relative isolate mt-32 px-6 py-32 sm:mt-56 sm:py-40 lg:px-8">
        <svg class="absolute inset-0 -z-10 h-full w-full stroke-white/10 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
          <defs>
            <pattern id="1d4240dd-898f-445f-932d-e2872fd12de3" width="200" height="200" x="50%" y="0" patternUnits="userSpaceOnUse">
              <path d="M.5 200V.5H200" fill="none" />
            </pattern>
          </defs>
          <svg x="50%" y="0" class="overflow-visible fill-gray-800/20">
            <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
          </svg>
          <rect width="100%" height="100%" stroke-width="0" fill="url(#1d4240dd-898f-445f-932d-e2872fd12de3)" />
        </svg>
        <div class="absolute inset-x-0 top-10 -z-10 flex transform-gpu justify-center overflow-hidden blur-3xl" aria-hidden="true">
          <div class="aspect-[1108/632] w-[69.25rem] flex-none bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-20" style="clip-path: polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)" />
        </div>
        <div class="mx-auto max-w-2xl text-center">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Utilisez notre hébergeur aujourd'hui.</h2>
          <p class="mx-auto mt-6 max-w-xl text-lg leading-8 text-gray-300">Améliorer la sécurité et l'efficacité de votre serveur en intégrant dès aujourd'hui notre hébergeur de confiance, vous permettant ainsi de favoriser un environnement prospère et engagé.</p>
          <div class="mt-10 flex items-center justify-center gap-x-6">
            <a href="https://my.innohost.pro" class="rounded-md bg-white px-3.5 py-2.5 text-sm font-semibold text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Commencer</a>
            <a href="https://discord.gg/inno" class="text-sm font-semibold leading-6 text-white">Rejoignez notre discord <span aria-hidden="true">→</span></a>
          </div>
        </div>
      </div>
    </main>

    <!-- Footer -->
    <footer aria-labelledby="footer-heading" class="relative">
      <h2 id="footer-heading" class="sr-only">Footer</h2>
      <div class="mx-auto max-w-7xl px-6 pb-8 pt-4 lg:px-8">
        <div class="border-t border-white/10 pt-8 md:flex md:items-center md:justify-between">
          <div class="flex space-x-6 md:order-2">
            <a v-for="item in footerNavigation.social" :key="item.name" :href="item.href" class="text-gray-500 hover:text-gray-400">
              <span class="sr-only">{{ item.name }}</span>
              <component :is="item.icon" class="h-6 w-6" aria-hidden="true" />
            </a>
          </div>
          <p class="mt-8 text-xs leading-5 text-gray-400 md:order-1 md:mt-0">&copy; 2024 Inno-Host, Inc. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { defineComponent, h } from 'vue'
import {
  ArrowPathIcon,
  ChevronRightIcon,
  CloudArrowUpIcon,
  Cog6ToothIcon,
  FingerPrintIcon,
  LockClosedIcon,
  ServerIcon,
} from '@heroicons/vue/20/solid'
import { BoltIcon, AdjustmentsHorizontalIcon, UsersIcon } from '@heroicons/vue/24/outline'
const primaryFeatures = [
  {
    name: 'Gratuité',
    description:
      'InnoHost offre un hébergement gratuit pour vos bots Discord, ce qui vous permet de démarrer sans frais initiaux.',
    icon: BoltIcon,
  },
  {
    name: 'Fiabilité',
    description:
      'Notre infrastructure est conçue pour offrir une disponibilité maximale, garantissant que vos bots restent opérationnels et accessibles à tout moment.',
    icon: UsersIcon,
  },
  {
    name: 'Performance',
    description:
      'Avec des serveurs optimisés et une connectivité rapide, vos bots bénéficieront de performances exceptionnelles, assurant une expérience fluide pour vos utilisateurs.',
    icon: AdjustmentsHorizontalIcon,
  },
]
const secondaryFeatures = [
  {
    name: 'Sécurité',
    description: 'La sécurité est une priorité chez InnoHost. Nous utilisons des mesures de sécurité avancées pour protéger vos données et garantir la confidentialité de vos utilisateurs.',
    icon: FingerPrintIcon,
  },
  {
    name: 'Facilité d\'utilisationn',
    description: 'Notre plateforme est conviviale et facile à utiliser, ce qui vous permet de déployer et de gérer vos bots Discord en quelques clics seulement.',
    icon: Cog6ToothIcon,
  },
  {
    name: 'Latence',
    description: 'Bénéficiez de temps de réponse ultra-rapides grâce à notre infrastructure optimisée, garantissant une latence minimale pour des performances ininterrompues.',
    icon: CloudArrowUpIcon,
  },
]
const stats = [
  { id: 1, name: 'Utilisateurs', value: 'N/A' },
  { id: 2, name: 'Uptime', value: '99.9%' },
  { id: 3, name: 'Serveurs enregistrés', value: 'N/A' },
]
const footerNavigation = {
  solutions: [
    { name: 'Hosting', href: '#' },
    { name: 'Data Services', href: '#' },
    { name: 'Uptime Monitoring', href: '#' },
    { name: 'Enterprise Services', href: '#' },
  ],
  support: [
    { name: 'Pricing', href: '#' },
    { name: 'Documentation', href: '#' },
    { name: 'Guides', href: '#' },
    { name: 'API Reference', href: '#' },
  ],
  company: [
    { name: 'About', href: '#' },
    { name: 'Blog', href: '#' },
    { name: 'Jobs', href: '#' },
    { name: 'Press', href: '#' },
    { name: 'Partners', href: '#' },
  ],
  legal: [
    { name: 'Claim', href: '#' },
    { name: 'Privacy', href: '#' },
    { name: 'Terms', href: '#' },
  ],
}
</script>
