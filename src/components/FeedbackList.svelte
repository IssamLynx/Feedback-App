<script>
  import {FeedbackStore} from '../stores'
  import FeedbackItem from './FeedbackItem.svelte'

</script>

{#each $FeedbackStore as fb (fb.id)}
  <FeedbackItem item={fb} />
{/each}
Footer
© 2023 GitHub, Inc.
