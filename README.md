# Canto Frierenbench

<img width="960" alt="frierenbench" src="https://github.com/user-attachments/assets/65cd3b1a-96f0-4d12-aded-ed525b921dfc" />

An LLM benchmark based on the first episode of Cantonese dubbed Friren to test the generation of [langpal subtitle](https://langpal.com.hk/subtitles) formatted SRT files that have duel Cantonese and English.

Expected Format:
```
1
00:00:00,672 --> 00:00:04,960
(yue)粵文字幕:
www.cantocaptions.com
(en) Cantonese subtitles:
www.cantocaptions.com

2
00:01:30,406 --> 00:01:33,659
(yue)（遙遠嘅大陸北方盡頭）
(en) (The northern end of the distant continent)
```

The extension uses the language prefixs to correctly display duel subtitles on a variety of different platforms.

The original spoken Cantonese subtitles are provided by [www.cantocaptions.com](https://cantocaptions.com)

The prompt to put into any given LLM is available here at `./frieren-prompt.txt`.
