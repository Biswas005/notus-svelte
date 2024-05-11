<script>
  // core components
  import CardStats from "components/Cards/CardStats.svelte";
</script>

<!-- Header -->
<div class="relative bg-red-500 md:pt-32 pb-32 pt-12 isolate aspect-video w-96 rounded-xl backdrop-filter backdrop-blur-lg">
  <div class="px-4 md:px-10 mx-auto w-full backdrop-blur-sm hover:backdrop-blur-lg">
    <div>
      <!-- Card stats -->
      <div class="flex flex-wrap backdrop-blur-sm hover:backdrop-blur-lg">
        <div class="w-full lg:w-6/12 xl:w-3/12 px-4 backdrop-blur-sm hover:backdrop-blur-lg">
          <CardStats
            statSubtitle="TRAFFIC"
            statTitle="350,897"
            statArrow="up"
            statPercent="3.48"
            statPercentColor="text-emerald-500"
            statDescripiron="Since last month"
            statIconName="far fa-chart-bar"
            statIconColor="bg-red-500"
          />
        </div>
      </div>
    </div>
  </div>
</div>