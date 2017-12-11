<template>
	<div>
		<baseInputText v-model="newTodotext" placeholder="new" todo="" @keydown.enter="addTodo">
		</baseInputText>
	</div>
</template>