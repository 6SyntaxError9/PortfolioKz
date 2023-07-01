<script>
	import ItemCard from './ItemCard.svelte';
</script>

<div class="mb-5">
	<ItemCard
		timespan="June-July 2022"
		href="https://github.com"
		role="Inhouse AWS internship"
		short_desc="Team Leader"
		external_links={[
			{
				label: 'GitHub',
				url: 'https://github.com/'
			}
		]}
		tags={[]}
	>
	In this work, we have developed a virtual lab using the services that AWS offers. This lab can be
	assessed by the students, faculties and lab assistants if they are offered IAM policies based on
	their roles. Students need not worry if they carry out their work on different machines as this
	virtual lab will allow them to continue their work from anywhere , anytime just by having an
	internet connection. This concept of virtual lab can be implemented in all the labs of the different departments & can
	thus provide students a better hands on experience
	</ItemCard>
</div>
