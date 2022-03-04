<script>
	import ConnectButton from "$lib/ConnectButton/ConnectButton.svelte";
	import { selectedAccount, connected, chainId } from 'svelte-web3';
	
	let account, chain;
	$: account = ($connected) ? $selectedAccount : "---";
	$: chain = ($connected) ? $chainId : "---";
</script>


<svelte:head>
    <title>SvelteKit Web3 Demo</title>
</svelte:head>


<div>
	<h1>SvelteKit Web3 Demo App</h1>

	<p>Featuring Svelte-Web3 and a Web3Modal button for MetaMask and WalletConnect.</p>
	
	<ConnectButton />

	<p> ChainId: {chain} | Account: {account}</p>
</div>
