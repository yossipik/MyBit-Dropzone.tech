---
id: ERC20Airdrop
title: ERC20Airdrop
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> ERC20Airdrop</h2><div class="source">Source: <a href="git+https://github.com/MyBitFoundation/MyBit-Dropzone.tech/blob/v1.0.0/contracts/ERC20Airdrop.sol" target="_blank">ERC20Airdrop.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="ERC20Airdrop.html#LogTokensTransferred">LogTokensTransferred</a></li><li><a href="ERC20Airdrop.html#">fallback</a></li><li><a href="ERC20Airdrop.html#onlyContracts">onlyContracts</a></li><li><a href="ERC20Airdrop.html#sendAirdrop">sendAirdrop</a></li><li><a href="ERC20Airdrop.html#sendAirdropEqual">sendAirdropEqual</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="events"><h3>Events</h3><ul><li><div class="item event"><span id="LogTokensTransferred" class="anchor-marker"></span><h4 class="name">LogTokensTransferred</h4><div class="body"><code class="signature">event <strong>LogTokensTransferred</strong><span>(address _tokenAddress, address _sender, uint _totalAmount) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_tokenAddress</code> - address</div><div><code>_sender</code> - address</div><div><code>_totalAmount</code> - uint</div></dd></dl></div></div></li></ul></div><div class="modifiers"><h3>Modifiers</h3><ul><li><div class="item modifier"><span id="onlyContracts" class="anchor-marker"></span><h4 class="name">onlyContracts</h4><div class="body"><code class="signature">modifier <strong>onlyContracts</strong><span>(address _tokenAddress) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_tokenAddress</code> - address</div></dd></dl></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>(address _mybTokenBurner) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_mybTokenBurner</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="sendAirdrop" class="anchor-marker"></span><h4 class="name">sendAirdrop</h4><div class="body"><code class="signature">function <strong>sendAirdrop</strong><span>(address _tokenAddress, address[] _recipients, uint[] _amounts) </span><span>external </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="ERC20Airdrop.html#onlyContracts">onlyContracts </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_tokenAddress</code> - address</div><div><code>_recipients</code> - address[]</div><div><code>_amounts</code> - uint[]</div></dd></dl></div></div></li><li><div class="item function"><span id="sendAirdropEqual" class="anchor-marker"></span><h4 class="name">sendAirdropEqual</h4><div class="body"><code class="signature">function <strong>sendAirdropEqual</strong><span>(address _tokenAddress, address[] _recipients, uint _amount) </span><span>external </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="ERC20Airdrop.html#onlyContracts">onlyContracts </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_tokenAddress</code> - address</div><div><code>_recipients</code> - address[]</div><div><code>_amount</code> - uint</div></dd></dl></div></div></li></ul></div></div></div>