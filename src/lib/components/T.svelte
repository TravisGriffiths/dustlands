<script lang="ts">
   export let c: string = '';

   let classStr: string = 'font-bold';
   const getClassStr = (dec: string) => {
      let classes: Array<string> = []
      if (dec.match("b")) classes = [...classes, 'font-bold']
      if (dec.match("s")) classes = [...classes, 'font-semibold']
      if (dec.match("u")) classes = [...classes, 'underline']
      return classes.join(' ')
   }
   $: classStr = getClassStr(c)
</script>

<span class={classStr}>
   <slot />
</span>

