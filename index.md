
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-W53Z32X"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

## Welcome to Arrow Cardano Staking pool

We here at **Arrow** cardano staking pool want our stake holders benefit the most with the lowest feasible fixed and variable fees. Similar to a lavendar flower provides both a very pleasant aroma around it's surroundings and at the same time provides a high nector content for honey bees, let both of us (pool operators and stake holders) flourish together

You can use use my pool id [ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8](https://cardanoscan.io/pool/ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8) to stake you cardano.

Our servers are located on highly fail safe and efficient Linux environment maintained 24x7 by technical professionals with decades of experience. These servers as running with an uptime of 99.999%

### Future plans

As you can see this website is very preliminary and under development. We do not believe in a lot of bells and whistles just for the sake of attracing customers. We are going to add many more features in the near future. We will also be adding several stats, metrics and helpful data for ADA stakers to make informed choices.

```
Facts to consider while you choose your pool

- We offer Lowest possible EPOH fee OF 340 ADA.
- Lowest possible variable fee of 10%. Lowest is NOT always better. Check THE link provided below.
- Fees will go down as more people join this pool.
- We will adjust future fee structure in alighment to the IOHK algorithm for the optimal benefit of the stake holders.
- Feature rich website coming in the near future

- Do not get carried away by operators offering 0% fees and with high saturation of funds. 
- In most cases operators with low fees will not be able to sustain and offer 99.99% uptime thus missing out on ADA rewards
- Low fee and high saturation of funds is not always good for the IOHK rewards algorithm. See article below
```
**IOHK algorithm will not always favor saturated pools** [Check this article](https://www.reddit.com/r/cardano/comments/ejie0c/cardano_staking_what_drives_returns_how_to_pick/)  Make an informed decision of your liking and also help operators with low stake to promote true decentralization of the Cardano eco system.

<a href="https://twitter.com/ADAarrowPool?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @ADAarrowPool</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

**Check some pool stats below**

<script  src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script>
$.getJSON('https://js.adapools.org/pools/ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8/summary.json', function(data) { 
$.each( data.data, function( i, val ) { 
		a=new Array('tax_fix','pledge','total_stake');
		if(parseInt(val) > 100000) val=Math.round(parseInt(val)/1000000);
		if(i=='blocks_lifetime') val=parseInt(val) + parseInt(data.data.blocks_epoch);

		$('#ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_'+i).html(val).text();   
}); 
		});
</script>

Pool ID: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_pool_id"></span><br>
		Ticker: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_db_ticker"></span><br>
		Name: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_db_name"></span><br>
		Description: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_db_description"></span><br>
		Total Stake: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_total_stake"></span><br>
		Last Reward Epoch: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_rewards_epoch"></span><br>
		Tax Ratio: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_tax_ratio"></span><br>
		Tax Fix: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_tax_fix"></span><br>
		ROA: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_roa">%</span><br>
		Blocks Lifetime: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_blocks_lifetime"></span><br>
		Blocks in epoch: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_blocks_epoch"></span><br>
		Pledge: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_pledge"></span><br>
		Rank: <span id="ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8_rank"></span><br>
		More info on <a href="https://adapools.org/pool/ef02b13ef062236829d567178288b8079cb2a924008734fc07ffd5b8">ADApools.org</a>.
