<script>
export default {
  data() {
    return {
      buttons: [
        { id: 0, name: 'Beyaz Eşya Servisi' },
        { id: 1, name: 'Buzdolabı Tamiri' },
        { id: 2, name: 'Buzdolabı Tamiri' },
        { id: 3, name: 'Çamaşır Makinesi Tamiri' },
        { id: 4, name: 'Bulaşık Makinesi Tamiri' },
        { id: 5, name: 'Bulaşık Makinesi Tamiri' },
        { id: 6, name: 'Fırın Tamiri' },
        { id: 7, name: 'Davlumbaz Tamiri' },
        { id: 8, name: 'Küçük Ev Aletleri Tamiri' }
      ],
      highlightedButton: null,
    };
  },
  methods: {
    highlightButton(id) {
      this.highlightedButton = id;
    },
  },
};
</script>

<template>
  <!-- Top Half -->
  <div class="flex flex-col xl:flex-row">
    <!-- Top Left -->
    <div class="max-xl:justify-center max-xl:items-center mx-auto">
      <!-- First -->
      <div class="flex xl:p-10 md:p-14">
        <div>
          <img src="./images/fix-store.png" class="" />
        </div>
        <div>
          <div class="text-blue-500 text-[13px] font-sans font-medium leading-[30px]">
            Kasım 2021’den beri üye
          </div>
          <div class="font-bold">
            Fatih Keskin
          </div>
          <div>Keskin Soğutma ve Beyaz Eşya</div>
          <div class="flex flex-row">
            <img src="./icons/carbon_location.svg" class="" />
            <div>
              <div class="">Atatürk mahallesi, Sakarya sokağı, No: 13/5</div>
              <div class="">Ataşehir / Anadolu Yakası / İstanbul</div>
            </div>
          </div>
        </div>
      </div>
      <!-- Second -->
      <div class="flex max-md:flex-col md:flex-1 max-xl:justify-center">
        <div class="m-10 max-md:mx-auto">
          <div class="flex flex-row">
            <img src="./icons/tabler_star.svg" class="" />
            <div>4.3</div>
          </div>
          <span>26 kişi değerlendirdi</span>
          <button class="h-[42px] w-[152px] bg-blue-500 flex items-center justify-center rounded-[10px]"><img
              src="./icons/ant-design_edit-outlined.svg" class="" />Değerlendir</button>
          <button class="w-[152px] h-[42px] bg-green-600 flex items-center justify-center rounded-[10px]"><img
              src="./icons/solar_phone-bold.svg" class="" />Hemen Ara</button>
        </div>
        <!-- Vertical Line Break -->
        <div class="hidden md:inline-block h-[250px] min-h-[1em] w-0.5 self-stretch bg-slate-300 opacity-100"></div>
        <hr class="md:hidden my-6 h-0.5 border-t-0 mx-32 bg-slate-300 opacity-100 dark:opacity-50" />
        <div class="m-10 max-md:mx-auto">
          <div class="">
            290 kez hizmet verdi
          </div>
          <div class="flex flex-row items-center">
            Hız
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
          </div>
          <div class="flex flex-row items-center">
            Fiyat
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
          </div>
          <div class="flex flex-row items-center">
            Kalite
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
          </div>
          <div class="flex flex-row items-center">
            Hız
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
          </div>
          <div class="flex flex-row items-center">
            Nezaket
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
            <img src="./icons/tabler_star.svg" />
          </div>
        </div>
        <!-- Vertical Line Break -->
        <div class="hidden md:inline-block md:h-[250px] min-h-[1em] w-0.5 self-stretch bg-slate-300 opacity-100"></div>
        <hr class="md:hidden my-6 h-0.5 border-t-0 mx-32 bg-slate-300 opacity-100 dark:opacity-50" />
        <div class="m-10 max-md:mx-auto">
          <div class="flex flex-row">
            <img src="./icons/material-symbols-light_verified-rounded.svg" class="" />
            <span>Onaylanmış Belgeler</span>
          </div>
          <ul class="list-disc text-blue-500 text-[13px] font-medium leading-[30px]">
            <li class="text-zinc-500">Kimlik</li>
            <li class="text-zinc-500">Vergi Levhası</li>
            <li class="text-zinc-500">Cep Telefonu</li>
            <li class="text-zinc-500">E-Posta</li>
          </ul>
        </div>
      </div>
    </div>
    <!-- Top Right -->
    <div class="w-[597px] h-[371px] bg-slate-100 rounded-xl m-10 max-xl:justify-center max-xl:items-center mx-auto">
      <div class="bg-white w-20 rounded-md">Hakkında</div>
      <div class="m-10">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
    </div>
  </div>
  <!-- Bottom Half -->
  <!-- Bottom Left -->
  <!-- First -->
  <div>
    <div>Hizmet Verdiği Sektörler</div>
    <div className="mb-28 max-w-[53rem] text-center sm:mb-40">
      <div class="flex flex-wrap">
        <button v-for="button in buttons" :key="button.id" @click="highlightButton(button.id)"
          :class="{ 'bg-blue-500 border-none': button.id === highlightedButton }"
          class="m-2 py-2 px-4 border border-slate-300 rounded-lg cursor-pointer transition">
          {{ button.name }}
        </button>
      </div>
    </div>
  </div>
  <!-- Second -->
  <div>
    <div>Hizmet Verdiği İlçeler</div>
    <div className="mb-28 max-w-[53rem] text-center sm:mb-40">
      <div class="flex flex-wrap">
        <button v-for="button in buttons" :key="button.id" @click="highlightButton(button.id)"
          :class="{ 'bg-blue-500 border-none': button.id === highlightedButton }"
          class="m-2 py-2 px-4 border border-slate-300 rounded-lg cursor-pointer transition">
          {{ button.name }}
        </button>
      </div>
    </div>
  </div>
  <!-- Bottom Right -->
</template>
