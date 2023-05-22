# Performance
Collect performance info for vue page

## Examples

Vue hook
```
<!-- ./src/Home.vue -->
<script setup>
...
import usePerformance from 'performance/usePerformance'
const { observeAndSubmit } = usePerformance()
onMounted(() => {
  observeAndSubmit({
    ele,
    next,
    duration
  })
})
...
</script>


```
