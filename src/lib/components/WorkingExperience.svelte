<script>
    import { Timeline, TimelineItem } from 'flowbite-svelte';
    import { CalendarWeekSolid } from 'flowbite-svelte-icons';
  </script>
  
  <Timeline order="vertical" class="container mx-auto px-4 py-8">
    <TimelineItem title="Rezid.net - COO | Product Management and Customer Success" date="2019-2024">
      <svelte:fragment slot="icon">
        <span class="flex absolute -start-3 justify-center items-center w-6 h-6 bg-primary-200 rounded-full ring-8 ring-white dark:ring-gray-900 dark:bg-primary-900">
          <CalendarWeekSolid class="w-4 h-4 text-primary-600 dark:text-primary-400" />
        </span>
      </svelte:fragment>
      <p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">Leading support, customer success, quality assurance (QA) and driving product requirements of Rezid.net - a startup delivering property management SaaS focusing on the hotel industry</p>
    </TimelineItem>
    <TimelineItem title="Clicksoftware - Project Manager" date="2016-2019">
      <svelte:fragment slot="icon">
        <span class="flex absolute -start-3 justify-center items-center w-6 h-6 bg-primary-200 rounded-full ring-8 ring-white dark:ring-gray-900 dark:bg-primary-900">
          <CalendarWeekSolid class="w-4 h-4 text-primary-600 dark:text-primary-400" />
        </span>
      </svelte:fragment>
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">Optimized AWS spend, cutting annual cloud costs by over $5M, and managed DevOps license procurement. Composed root cause analysis reports for service downtime, performed customer cost analysis for profitability adjustments, and developed data recovery procedures reducing regional disaster downtime to under 30 minutes.</p>
    </TimelineItem>
    <TimelineItem title="I Know First - Operations Manager" date="2015-2016">
      <svelte:fragment slot="icon">
        <span class="flex absolute -start-3 justify-center items-center w-6 h-6 bg-primary-200 rounded-full ring-8 ring-white dark:ring-gray-900 dark:bg-primary-900">
          <CalendarWeekSolid class="w-4 h-4 text-primary-600 dark:text-primary-400" />
        </span>
      </svelte:fragment>
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">Interned while completing my bachelor degree, hired as a full-time employee and later promoted to operations manager.</p>
    </TimelineItem>
  </Timeline>