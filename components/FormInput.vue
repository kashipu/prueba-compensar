<template>
  <div class="form-group">
    <label :for="id">{{title}}</label>
    <input
      :type="modeType"
      class="form-control"
      :id="id"
      :placeholder="placeholder"
    />
  </div>
</template>

<script>
export default {
	props: {
		title: String,
		id: String,
		modeType: String,
		placeholder: String
	}
}
</script>

<style>
label {
  font-weight: bold;
}

</style>
