<script setup lang="ts">
import {
  cloneDeep,
  //   isEqual,
  // merge
} from "lodash-es";

const objectToClone = {
  a: 'a',
  b: 'b',
  c: 'c',
  d: {
    a: 'a',
    b: 'b',
    c: 'c',
  }
}

const cloned = cloneDeep(objectToClone)
console.log(cloned)
// const merged = merge(objectToClone, cloned)
//
// console.log(isEqual(cloned, objectToClone))

// console.log(merged)
</script>

<template>
  some text
</template>
