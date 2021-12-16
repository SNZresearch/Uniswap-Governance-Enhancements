## 1. UNI Can be used as Initial Uniswap Offering（IUO）token

Uni being a IUO token not means  

### 1.1 necessity

Uniswap has been the most valuable dex for a long time. **In secondary market**, no DeFi protocols will supersede Uniswap. Howerver, the biggest problem DeFi startups faced is ,/ that they cannot easily get enough fund to transform ideas into reality **Primary market.** If Uniswap can help to buidl this tranparent financial infrastructure for Primary market, then DeFi startups save their efforts from begging for Crypto VCs to understand their ideas and invest. That's real **UNI_invest_DAO.**

### 1.2 DAOs Treasury 

**Treasury Top 10 Projects**
**​**

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639648507301-40fa1f99-7290-460e-852b-a5bd9cdf0a84.png#clientId=u2003d281-2323-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=400&id=u598a818e&margin=%5Bobject%20Object%5D&name=image.png&originHeight=799&originWidth=669&originalType=binary&ratio=1&rotation=0&showTitle=false&size=68484&status=done&style=none&taskId=uf275b0a5-397f-44e7-81a1-33338fc860d&title=&width=334.5)


December 16th, 2021 from [https://openorgs.info/](https://openorgs.info/)
Uniswap has the most treasury among top 10 projects and takes more responsibility than other projects.

### 1.3 buidl Uniswap IUO Tools (Using Uniswap's Universal AMM)

[https://www.paradigm.xyz/2021/06/uniswap-v3-the-universal-amm/](https://www.paradigm.xyz/2021/06/uniswap-v3-the-universal-amm/)
As the article above states, Uniswap can Simulate a lot of  AMM curves.  Despite the fact that there are some mistakes in this article, it does inspire peole that we can buidl a IUO Tools Using Uniswap V3.
​

**One of the logical vulnerabilities of the article is as follows:**
Once  the simulating process of other curvess finished, that means The shape of liquidity and ticks is fixed and looks like other curves. However after the process memtioned above, if people add liquidity on certain ticks, the shape of liquidity and ticks will change thus out of the intial simulating curve.
​

**this logical vulnerablity is exciting if we change it into an advantage:**
​

Once we just set a time lock during which only the DeFi startups (which was aproved by UNI Grant) can put UNI-XXX  liquidity into the pool, and people are to buy 
​

### 1.4 designing IUO process 

The DeFi startup X need fund and offer XXX token. The valuation of A is **10 million** dollars and need **1 million **dollars.The total number of XXX tokens is **1 billion**, and 100 million tokens was participating in this IUO process.
Assume UNI price is 20 USDC when X applying IUO.  The remaining XXX tokens not invloving IUO will be locked for 1 year, which X will should promise and write it into a smart contract.
​


1. X apply for 50 thousands of  UNI and offering 1million XXX (50k UNI——1m XXX).
1. The voters who likes this project gather 50k UNI(if 50k UNI not fullfilled only 25k UNI gathered , then process 3 won't happen and  X get 25k UNI and give away 1m XXX )
1. Before the time lock , only the voters decide which IUO simulating curve the IUO process adopts and put intial liquidity into UNI-XXX pool.
1. During the time lock(1 day), investors can only buy XXX with UNI. Nobody could sell back XXX (which is written in the smart contract) 
1. After the time lock. X take fixed 50k UNI away, and voters will withdraw parts of  XXX to keep the price stable, and remaining LP UNI-XXX will be realeased in 12 months.



Let's take some examples.
a. 1st IUO curve(default)  is simulating Uniswap V2
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639665760042-b6789389-b5b6-43ce-a19e-7efceb884c53.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=229&id=u51e73ea5&margin=%5Bobject%20Object%5D&name=image.png&originHeight=458&originWidth=655&originalType=binary&ratio=1&rotation=0&showTitle=false&size=22895&status=done&style=none&taskId=u6363bd6d-30b6-4b68-b131-29e6f701f3b&title=&width=327.5)


- before time lock, the intial pool, 50k UNI-1000k XXX
- during time lock, investors use 50k UNI to buy 500k XXX

pool: 100k UNI-500k XXX

- after time lock, X get 50k UNI(a fixed number from inital pool)

pool remaining: 50k UNI- 500k XXX. In order to keep the price stable(from 100k UNI-500K XXX to 50k UNI to 250k XXX ),Voters get 250k XXX vesting for 12months . the 50k UNI- 250k XXX LP tokens are owned by the voters.


b. 2nd curve is simulating a single position in Uniswap v3 that means 
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639666070784-13c55fe0-0f21-47ca-ab53-f42ce2cc5473.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=218&id=ued0e0d6f&margin=%5Bobject%20Object%5D&name=image.png&originHeight=436&originWidth=579&originalType=binary&ratio=1&rotation=0&showTitle=false&size=18325&status=done&style=none&taskId=u7e363f5c-d832-4cd4-ac3a-017afcc3bb1&title=&width=289.5)


- before time lock,the initial pool, 50k UNI-1000K XXX and all XXX was put on $0.02 price.
- During time lock, investors use 20k UNI to buy 200K XXX (XXX: $0.02)

pool: 70k UNI-800k XXX

- after time lock, X get 50k UNI(a fixed number from initial pool)

pool remaininig:20k UNI-800k XXX. In order to keep the price stable(XXX: 0.02, from 20k UNI-800k XXX to 20k UNI-200k XXX), Voters get 600 XXX vesting 12 moths. the 20k UNI- 200k XXX LP tokens are owned by the voters.


c. 3rd curve is simulating a two-asset Balancer pool 


![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639666095114-6ae027a7-3e9f-403f-b368-4ed759c79d81.png#clientId=u03e41dc2-6c6e-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=181&id=rY1xQ&margin=%5Bobject%20Object%5D&name=image.png&originHeight=361&originWidth=511&originalType=binary&ratio=1&rotation=0&showTitle=false&size=17990&status=done&style=none&taskId=ue611217f-3db4-47a8-9655-360456f013c&title=&width=255.5)


That't same  because X take fixed 50k UNI away and voters will withdraw parts of  XXX to keep the price stable, and remaining LP UNI-XXX will be realeased in 12 months. The diffrence is the curve shape  make voters have more advantage that investors after. 


In this process: 
UNI Grants could be voters and participate in IUO process instead of just give UNI grants away. and if the votes come from UNI,then the XXX tokens will be burn after the time lock.
So IUO will make UNI Grants have greater capital capital efficiency. And Since all voters have to give away their UNI tokens instead of show their UNI tokens numbers, whale doesn't have any advantage against small investors.
​

SO, how can we distinguished whales from small investors, that's an another story in  Uniswap Governance Enhancements Part 2. 


## 2. Chain analysis and classification of Uniswap users' trading behaviour 

Trading Volume and Trading times of different addresses 
weth-usdc 0.05% from 2021-08-18 to 2021-12-15
​

Total Swap Volume of  addresses
eg： Swap Volume between (0,  100,000) dollars : 124106 addresses 
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639696726248-35fd2d20-786b-4ef5-a0a8-f3dafea84f9d.png#clientId=ub033e3e6-1be2-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=u6ff5c3b2&margin=%5Bobject%20Object%5D&name=image.png&originHeight=584&originWidth=1304&originalType=url&ratio=1&rotation=0&showTitle=false&size=14603&status=done&style=none&taskId=u3fabbfcd-551f-41e5-adc5-56bba505243&title=)


Total number of addresses which swap between (0, 100,000) times
eg: Swap times between (0,  5) dollars : 127371 addresses 
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639694655158-d6c6f663-048e-4f7c-b611-b9b5b6edae8f.png#clientId=ub033e3e6-1be2-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=ud40f1ee3&margin=%5Bobject%20Object%5D&name=image.png&originHeight=584&originWidth=1304&originalType=url&ratio=1&rotation=0&showTitle=false&size=12972&status=done&style=none&taskId=u530ec8a7-ccae-4b7e-a421-088232e0747&title=)


Total number of addresses which swap between (0, 100) times
​

![image.png](https://cdn.nlark.com/yuque/0/2021/png/1230808/1639694660508-a7916724-0e94-4687-8061-06e68010be66.png#clientId=ub033e3e6-1be2-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=uc290cc55&margin=%5Bobject%20Object%5D&name=image.png&originHeight=584&originWidth=1304&originalType=url&ratio=1&rotation=0&showTitle=false&size=15522&status=done&style=none&taskId=u93b8d255-218a-40a2-bc2c-a7feeb43247&title=)


Most trading of small investors did (1, 5) times trading and their trading volume is (0,100,000) dollars.
