<script>
import { h } from 'vue';

export default {
  props: {
    level: {
      type: Number,
      default: 1,
    },
    text: {
      type: String,
      default: '',
    },
  },
  render() {
    return h(`h${this.level}`, this.text);
  },
};
</script>

<style></style>
