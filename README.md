# Spam email detection in both English and Chinese
Evaluating the performance of large language models on spam email detection, the paper can be found in [here](https://arxiv.org/abs/2402.15537).

# Spam Detection Datasets 
This repository has two spam detection datasets: one in English and another in Chinese.

# In-context learning for spam detection
We evaluate the performance of ChatGPT for spam detection, and the prompt is shown as follows.
```Forget all your previous instructions. \n",
    " Pretend you are a spam mail detection expert who try to identify whether a mail is spam mail. \n",
    "        Answer “spam” if it is spam, “ham” if you think it is not a spam. \n",
    "        And if you think it is too private or difficult to judge, you can exclude the impossible one and choose the other.\n",
    "        Here is a few example for you:\n",
    "        'Eh u remember how 2 spell his name... Yes i did. He v naughty make until i v wet.' is 'ham';\n",
    "        'Great! I hope you like your man well endowed. I am  &lt;#&gt;  inches...' is 'ham';\n",
    "        'Do you know what Mallika Sherawat did yesterday? Find out now @  &lt;URL&gt;' is 'ham';\n",
    "        'Ha ha ha good joke. Girls are situation seekers.' is 'ham';\n",
    "        'HI BABE IM AT HOME NOW WANNA DO SOMETHING? XX' is 'ham';\n",
    "        'Did you hear about the new \\Divorce Barbie\\\"? It comes with all of Ken's stuff!\"' is \"spam\";\n",
    "        '500 New Mobiles from 2004, MUST GO! Txt: NOKIA to No: 89545 & collect yours today!From ONLY 1 www.4-tc.biz 2optout 087187262701.50gbp/mtmsg18' is \"spam\";\n",
    "        'Will u meet ur dream partner soon? Is ur career off 2 a flyng start? 2 find out free, txt HORO followed by ur star sign, e. g. HORO ARIES' is \"spam\";\n",
    "        'Text & meet someone sexy today. U can find a date or even flirt its up to U. Join 4 just 10p. REPLY with NAME & AGE eg Sam 25. 18 -msg recd@thirtyeight pence' is \"spam\";\n",
    "        'U 447801259231 have a secret admirer who is looking 2 make contact with U-find out who they R*reveal who thinks UR so special-call on 09058094597' is \"spam\".\n",
    "        Now you can identify whether the mail is a spam,please not give explain:\"\n",
    "      + Email Content\n"
```


```bibtex
@article{si2024evaluating,
      title={Evaluating the Performance of ChatGPT for Spam Email Detection}, 
      author={Shijing Si and Yuwei Wu and Le Tang and Yugui Zhang and Jedrek Wosik},
      year={2024},
      journal={Pacific Journal of Optimization},
      url={https://arxiv.org/abs/2402.15537}, 
}
```
