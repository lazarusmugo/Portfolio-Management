<script>
  import Icon from '@iconify/svelte';
  let activeTab = 'dashboard';
  function setActive(tab) {
    activeTab = tab;
  }
</script>

<nav class="fixed bottom-0 left-0 right-0 bg-white border-t border-gray-300 flex justify-around py-2">
  <a
    href="/"
    class="flex flex-col items-center text-gray-500 {activeTab === 'dashboard' ? 'active-link' : ''}"
    on:click={() => setActive('dashboard')}
  >
    <Icon icon="ic:round-dashboard" class="text-4xl mb-1" />
    Dashboard
  </a>
  <a
    href="/"
    class="flex flex-col items-center text-gray-500 {activeTab === 'properties' ? 'active-link' : ''}"
    on:click={() => setActive('properties')}
  >
    <Icon icon="bx:buildings" class="text-4xl mb-1" />
  Properties
  </a>
  <a
    href="/"
    class="flex flex-col items-center text-gray-500 {activeTab === 'analytics' ? 'active-link' : ''} "
    on:click={() => setActive('analytics')}
  >
    <Icon icon="gridicons:line-graph" class="text-4xl mb-1" />
    Analytics
    
  </a>
  <a
    href="/"
    class="flex flex-col items-center text-gray-500 {activeTab === 'financials' ? 'active-link' : ''}"
    on:click={() => setActive('financials')}
  >
    <Icon icon="iconoir:credit-cards" class="text-4xl mb-1" />
    Financials
  </a>
  <a
    href="/"
    class="flex flex-col items-center text-gray-500 {activeTab === 'notifications' ? 'active-link' : ''}"
    on:click={() => setActive('notifications')}
  >
    <Icon icon="tabler:bell" class="text-4xl mb-1" />
    Notifications
  </a>
</nav>

<style>
  .active-link {
    color: #eaa91b;
  }
</style>
