

<body>

	<a href="/detailpagina">detail</a>
	<h1>Meet our team of experts</h1>

	<p>
		Wij zijn de enthousiaste studenten die de opleiding Front-end Design & Development volgen aan de
		HvA.
	</p>

	<div class="grid-container">
		<img src="/Lesley.JPG" class="studenten" alt="Lesley" />
		<div class="grid-item">D</div>

		<img src="/Zainab.JPG" class="studenten" alt="" />
		<div class="grid-item">F</div>

		<img src="/Eva.JPG" class="studenten" alt="" />
		<div class="grid-item">N</div>

		<img src="/Rukiya.JPG" class="studenten" alt="" />
		<div class="grid-item">D</div>

		<img src="/Akiko.JPG" class="studenten" alt="Akiko" />
	</div>
</body>

<style>
	p {
		margin-bottom: 20px;
	}

	.grid-container {
		display: grid;
		grid-template-columns: auto auto auto;
		background-color: #050542;
	}

	.grid-item {
		display: flex;
		justify-content: center;
		align-items: center;
		border: 1px solid rgba(192, 186, 186, 0.8);
		padding: 32px;
		font-size: 32px;
		text-align: center;
	}
</style>
