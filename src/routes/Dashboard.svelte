<script>
  import Icon from '@iconify/svelte';
</script>

<nav class="fixed bottom-0 left-0 right-0 bg-white border-t border-gray-300 flex justify-around py-2">
  <a href="/" class="flex flex-col items-center text-gray-500 hover:text-blue-500">
    <Icon icon="ic:round-dashboard" class="text-xl mb-1" />
    Dashboard
  </a>
  <a href="/property" class="flex flex-col items-center text-gray-500 hover:text-blue-500">
    <Icon icon="bx:buildings"class="text-xl mb-1" />
    Property
  </a>
  <a href="/analytics" class="flex flex-col items-center text-gray-500 hover:text-blue-500">
    <Icon icon="gridicons:line-graph" class="text-xl mb-1" />
    Analytics
  </a>
  <a href="/financials" class="flex flex-col items-center text-gray-500 hover:text-blue-500">
    <Icon icon="iconoir:credit-cards" class="text-xl mb-1" />
    Financials
  </a>
  <a href="/notifications" class="flex flex-col items-center text-gray-500 hover:text-blue-500">
    <Icon icon="tabler:bell" class="text-xl mb-1" />
    Notifications
  </a>
</nav>

