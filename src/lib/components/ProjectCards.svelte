<script>
	import ItemCard from './ItemCard.svelte';
	import AnimatedLink from './atoms/AnimatedLink.svelte';
</script>

<div class="projects md:space-y-2 mt-5">
	<ItemCard
		timespan="Final Year Engineering Project"
		href="https://github.com"
		role="Veggified"
		short_desc="Decentralized Food Supply"
		external_links={[
			{
				url: 'https://github.com/',
				label: 'report'
			},
			{
				url: 'https://github.com/',
				label: 'certificate'
			}
		]}
		tags={['Solidity', 'Truffle', 'Ganache', 'JavaScript', 'MySql', 'Bootstrap', 'PHP']}
	>
	The Decentralized Food Supply can provide a transparent and secure system for
	tracking products in the supply chain industry. The App's performance was found to be satisfactory,
	and the usability testing showed that the App was easy to use, even for participants with no prior
	experience in the supply chain industry. The security audit revealed no major security vulnerabilities
	in the smart contracts. The App can have a positive impact on the supply chain industry by providing
	greater transparency, security, and accountability to the participants in the supply chain.
	This system reduces costs, saves time, and increases trust and transparency.
		<AnimatedLink href="https://github.com">GitHub</AnimatedLink>
	</ItemCard>
	<ItemCard
		timespan="Sem-6 mini project"
		href="https://github.com/"
		role="😁or😩?"
		short_desc="Sentiment Analysis"
		external_links={[
			{
				url: 'https://github.com/',
				label: 'Sentiment Analysis'
			}
		]}
		tags={['Python', 'Django']}
	>
	In this machine learning project, we built a binary text classifier to know the sentiment behind the text is positive or
	negative.
	</ItemCard>
	<ItemCard
		timespan="Sem-4 mini project"
		href="https://github.com/"
		role="e Pharma"
		short_desc="Online Medicine"
		external_links={[
			{
				url: 'https://github.com/',
				label: 'Online Medicine'
			},
			{
				url: 'https://github.com/',
				label: 'ePharma'
			}
		]}
		tags={['JavaScript', 'MySQL', 'PHP', 'CSS']}
	>
	A user-friendly website to help people get medicine on time. This project is a complete medicine inventory management
	system
	</ItemCard>
</div>
