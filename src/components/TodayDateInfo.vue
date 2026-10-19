<script setup>
import dayjs from 'dayjs'
import utc from 'dayjs/plugin/utc'
import timezone from 'dayjs/plugin/timezone'

dayjs.extend(utc)
dayjs.extend(timezone)

const now = dayjs().tz('Europe/Warsaw')

const date = now.format('DD MMMM YYYY')
const day = now.format('dddd')

</script>

<template>
  <div>
  <p>{{ day }}</p>
  <p>{{ date }}</p>
  </div>
</template>
