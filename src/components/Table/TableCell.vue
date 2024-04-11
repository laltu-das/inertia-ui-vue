<script lang="ts" setup>

import { useTableCellClasses } from './useTableCellClasses'

const { tableCellClasses } = useTableCellClasses()
</script>
<template>
    <td :class="tableCellClasses">
        <slot></slot>
    </td>
</template>
