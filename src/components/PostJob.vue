<template>
	<div class="p-8">
		<div class="w-1/2 space-y-6 bg-white rounded p-8">
			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Position</label>
				<input v-model="form.position" id="position" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Program</label>
				<input v-model="form.program" id="program" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Vacancy</label>
				<input v-model="form.vacancy" id="vacancy" type="number" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Area of Assignment</label>
				<input v-model="form.area_of_assignment" id="area_of_assignment" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Period of Enagagement</label>
				<input v-model="form.engagement_period" id="engagement_period" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Salary Grade</label>
				<input v-model="form.salary_grade" id="salary_grade" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Status</label>
				<input v-model="form.employment_status" id="employment_status" type="text" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex flex-col md:flex-row items-center space-x-2 pr-0 md:pr-10">
				<label class="w-36 flex-shrink-0 text-right" for="position">Deadline</label>
				<input v-model="form.deadline" id="deadline" type="date" class="px-4 py-2 rounded-sm border w-full rounded-sm">
			</div>

			<div class="flex justify-center space-x-2">
				<a href="#" class="px-4 py-2 text-blue-600 hover:underline hover:text-blue-800">Cancel</a>
				<button class="bg-blue-600 hover:bg-blue-800 text-white rounded-sm px-4 py-2">Submit</button>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data () {
			return {
				form: {
					position: null,
					program: null,
					vacancy: null,
					area_of_assignment: null,
					engagement_period: null,
					salary_grade: null,
					employment_status: null,
					deadline: null,
				}
			}
		}
	}
</script>