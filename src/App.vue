<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
	<nav>코인시세보기프로그램</nav>

	<table>
		<thead>
			<tr>
				<th>한글명</th>
				<th>현재가</th>
				<th>전일대비</th>
				<th>거래대금</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>
					<div>도지코인</div>
					<div>DOGE/KRW</div>
				</td>
				<td>394</td>
				<td>
					<div>-0.76%</div>
					<div>-3.00</div>
				</td>
				<td>1,783,893백만</td>
			</tr>
			<tr>
				<td>
					<div>리플</div>
					<div>XRP/KRW</div>
				</td>
				<td>
					<div>+0.67%</div>
					<div>10.00</div>
				</td>
				<td>1500</td>
				<td>1,159,31백만</td>
			</tr>
			<tr>
				<td>
					<div>이더리움클래식</div>
					<div>ETC/KRW</div>
				</td>
				<td>85,340</td>
				<td>
					<div>-2.33%</div>
					<div>-2040</div>
				</td>
				<td>933,497백만</td>
			</tr>
		</tbody>
	</table>

	<footer>mingsung521@gmail.com</footer>
</template>

<style>
nav {
	font-size: 1.1rem;
	font-weight: bold;
	padding-bottom: 0.5rem;
	border-bottom: 1px solid #e2e2e2;
}

main {
	padding-top: 1rem;
	padding-bottom: 10rem;
}

footer {
	font-size: 0.9rem;
	color: grey;
	border-top: 1px solid #e2e2e2;
	padding-top: 0.5rem;
}
</style>
