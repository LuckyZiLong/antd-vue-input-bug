<template>
  <div>
    <Form style="width: 340px">
      <FormItem>
        <Input placeholder="输入" allow-clear>
          <template #prefix> Hello </template>
        </Input>
      </FormItem>
    </Form>
  </div>
</template>

<script setup lang="ts">
import { Form, FormItem, Input } from 'ant-design-vue';
</script>