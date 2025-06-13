## 6
## 7, 8
## 9, 10, 11, 12
## [庞众望](https://baijiahao.baidu.com/s?id=1834641092455296655)

### https://github.com/zou-group/CellVoyager
### https://github.com/scverse

## <p align="center"> *[Time is Money, Efficiency is Life](https://en.wikipedia.org/wiki/Time_is_Money,_Efficiency_is_Life)* </p>
![960px-Time_is_money,_Efficiency_is_life](https://github.com/user-attachments/assets/ac6eea06-fd3c-4f87-946b-1e250f7e2136)


## <p align="center"> *[Universe](https://en.wikipedia.org/wiki/Universe)* </p>
## <p align="center"> *欲文明其精神，先自野蛮其体魄* </p>
## <p align="center"> *Swimming across the Pacific Ocean* </p>
## <p align="center"> *Swimming across the Arctic Ocean* </p>

### *When you read a book, a paper or source code, you are communicating with the brightest minds in human history. This is actually the most "effective" way to communicate. This is also the quickest path to success.*

## <p align="center"> *兄弟登山, 各自努力, 让我们在顶峰相聚* </p>

### *A wild boar barged into the vegetable garden, eager to take a bite out of everything it saw.*
### *The messier your exploration, the richer the feast of knowledge you’ll uncover.*
### *Richard Feynmann — 'Study hard what interests you the most in the most undisciplined, irreverent and original manner possible.'*



### <p align="center"> *[At Harvard, knowledge enters my mind at a terrifying rate every day.](http://xhslink.com/a/jZMjaSoybOLdb)* </p>

---

## Goals 2025/5/30 - 6/20: 
### 0. Run 10km in 50 minutes, run a half marathon in 1 hour and 45 minutes, do 100 push-ups in a row, do 50 pull-ups in a row
### 1. Complete the study of all papers and source codes related to AlphaFold 2&3

---
## newest personal records
### 2025/6/1 6:09-8:21: run a half marathon in 1:51:53
### feat: 2025/6/7,  run 5km in 22:59
### feat: 2025/6/5,  40 pull-ups in a row
### feat: 2025/6/5,  60 push-ups in a row

---
## Current progress:
### 2025/5/30 7:00 - : study the paper of AlphaFold 3: [Accurate structure prediction of biomolecular interactions with AlphaFold 3](https://www.nature.com/articles/s41586-024-07487-w)  
### 2025/6/11 14:20- : [CellVoyager: AI CompBio Agent Generates New Insights by Autonomously Analyzing Biological Data](https://www.biorxiv.org/content/10.1101/2025.06.03.657517v1.full.pdf)
### The central purpose of CellVoyager is to find a single-cell analysis distinct from the ones conducted in the paper but still biologically interesting and in line with the research goals of the paper


```
2025/5/31: {"push ups + Mountain Climbers": 460}, {"cartwheels": 100 meters}, {"running": 5km}
2025/5/31 6:46-7:37: section "Network architecture and training"
2025/5/31 7:37-10:12: section "Accuracy across complex types"
2025/5/31 10:12-13:08: section "Predicted confidences track accuracy"
2025/5/31 13:08-14:29: section "Model limitations"
2025/5/31 14:29-14:57: section "Discussion"

Let’s tackle the hardest part now—this is the core and most challenging section of the paper.
2025/5/31 14:57-: section "Methods"
2025/5/31 14:57-: Full algorithm details, Supplementary information(https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-024-07487-w/MediaObjects/41586_2024_7487_MOESM1_ESM.pdf), 45 pages in total
2025/5/31 14:57-15:50: 1 Notation
2025/5/31 16:30-17:00: run 5km in 28min
2025/5/31 20:27-23:49: 2.1 Parsing(To be continued)


2025/6/1: {"push ups + Mountain Climbers": 110}, {"cartwheels": 0}, {"running": 21km}, {"pull ups +  Parallel Bar Dips": 100}
2025/6/1 6:09-8:21: run a half marathon in 1:51:53
2025/6/1 13:20-23:30: 2.1 Parsing

2025/6/2: {"pull ups +  Parallel Bar Dips": 300}
2025/6/2 6:45-7:06: 2.1 Parsing
2025/6/2 9:04-16:50 (Very sleepy, low efficiency): 2.2 Genetic search


2025/6/3: {"push ups + Mountain Climbers": 200}, {"cartwheels": 100 meters}
6/3 6:48-19:58(low efficiency): 2.2 Genetic search
6/3 19:58-20:44: 2.3 MSA processing
6/3 20:44-23:16: 2.4 Template search(To be continued)

2025/6/4:  {"running": 5km}, {"pull ups +  Parallel Bar Dips": 100}, {"cartwheels": 100 meters}, {"push ups + Mountain Climbers": 200}
6/4 6:15-7:00: run 5km in 24:36
6/4 7:44-15:17(low efficiency): 2.4 Template search

2025/6/5: {"running": 5km}, {"pull ups + Parallel Bar Dips": 100}, {"push ups + Mountain Climbers": 200}
6/5 6:21-6:46: run 5km in 24:35, Average Pace: 4:55 per kilometer

2025/6/6:  {"running": 5km},  {"pull ups + Parallel Bar Dips": 200}
6/6 6:17-6:43: run 5km in 24:53, Average Pace: 4:58 per kilometer
6/6 9:05-10:00: 2.5 Training data(To be continued)

2025/6/7: {"running": 5km}, {"pull ups + Parallel Bar Dips": 100}, {"push ups + Mountain Climbers": 200}
6/7 6:24-6:48: run 5km in 22:59, Average Pace: 4:35
6/7 7:55-16:20: 2.5 Training data
6/7 16:20-16:31: 2.6 Tokenization
6/7 18:05-22:10: 2.7 Cropping(To be continued)

2025/6/8: {"pull ups + Parallel Bar Dips": 100},
6/8 9:15-10:00: 2.7 Cropping(continued)
6/8 10:00-21:20: 2.8 Featurisation and model inputs
6/8 21:20-21:46: 3 Model architecture(To be continued)

Finally, we start learning the algorithm details. Let's do it!

2025/6/9: {"running": 5km}, {"pull ups + Parallel Bar Dips": 200}, {"push ups + Mountain Climbers": 200}, {"cartwheels": 100 meters}
6/9 8:06-10:42: Algorithm 1 Main Inference Loop. (Great ! The first algorithm is completed !)
6/9 10:42-11:35:  {"pull ups + Parallel Bar Dips": 200}, After completing 200 "pull ups + Parallel Bar Dips", my entire body feels invigorated, muscles relaxed, and my mind sharper than ever—pure bliss! Every drop of sweat was worth it. That post-workout physical + mental refreshment. Absolutely addictive !
6/9 12:56-21:52: 3.1 Input embeddings(To be continued)

2025/6/10: {"running": half marathon}, {"push ups + Mountain Climbers": 200}, {"cartwheels": 100 meters}
6/10 6:12-8:14:  run a half marathon in 1:54:32
6/10 10:11-10:25: 3.1 Input embeddings
6/10 10:25-20:51: 3.2 Sequence-local atom attention, (stop at "Algorithm 5 Atom attention encoder"(page 17))

2025/6/11: {"running": 5km}, {"pull ups + Parallel Bar Dips": 200}, {"push ups + Mountain Climbers": 200}, {"cartwheels": 100 meters}
6/11 6:05-6:30: run 5km in 23:59, Average Pace: 4:47
6/11 7:40-13:50: 3.2 Sequence-local atom attention (completed)

6/11 14:20-21:58:  [CellVoyager: AI CompBio Agent Generates New Insights by Autonomously Analyzing Biological Data](https://www.biorxiv.org/content/10.1101/2025.06.03.657517v1.full.pdf), ask DeepSeek to summarize this paper, now stop at page 1

2025/6/12: {"running": 5km}, {"pull ups + Parallel Bar Dips": 300}, {"push ups + Mountain Climbers": 120}, {"cartwheels": 100 meters}
6/12 6:19-6:48: run 5km in 28:41, Average Pace: 5:26  (very slow)
6/12 8:01-13:25: CellVoyager, 1 Introduction (page 1-2)
6/12 13:25-14:07: CellVoyager, 2 Related Work (page 2-3)
6/12 14:07-15:09: 3 CellVoyager Methodology (page 3-)
6/12 15:09-15:54: {"cartwheels": 100 meters}
6/12 15:54-16:40: 3 CellVoyager Methodology (page 3-)
6/12 21:00-22:18: 3.2 Analysis planning, Execution, and Replanning (page 5)

2025/6/13: {"running": 5km},
6/13 7:55-: CellVoyager, 4 Evaluating CellVoyager Analysis Generation with CellBench (page 5-)

```







