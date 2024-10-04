## <center> UniWav: Towards Unified Pre-training for Speech Representation Learning and Generation </center>

<center> Anonymous submission to ICLR 2025 </center> 



### <center> Audio Samples </center>

<center> !!! Wearing headphones is strongly recommended to judge the audio quality !!! </center>


### <center> Speech Tokenization & Resynthesis </center>
<center> Samples are randomly selected from LibriSpeech test-clean subset. </center>

| <span style="width:300px;"></span> |  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Ground Truth<br>256k bps | <audio src="samples/resyn/gt/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/gt/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/gt/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/gt/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/gt/61-70968-0026.wav" controls style="width:200px;" preload></audio> |
| SpeechTokenizer<br>500 bps | <audio src="samples/resyn/sptk500/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk500/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk500/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk500/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk500/61-70968-0026.wav" controls style="width:200px;" preload></audio> |
| HuBERT + Unit-HiFiGAN<br>500 bps | <audio src="samples/resyn/unitgan/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/unitgan/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/unitgan/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/unitgan/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/unitgan/61-70968-0026.wav" controls style="width:200px;" preload></audio> |
| UniWav<br>500 bps | <audio src="samples/resyn/uniwav500/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav500/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav500/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav500/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav500/61-70968-0026.wav" controls style="width:200px;" preload></audio> |
| SpeechTokenizer<br>1k bps | <audio src="samples/resyn/sptk1k/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk1k/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk1k/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk1k/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/sptk1k/61-70968-0026.wav" controls style="width:200px;" preload></audio> |
| UniWav<br>1k bps | <audio src="samples/resyn/uniwav1k/8463-287645-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav1k/2094-142345-0040.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav1k/4446-2273-0008.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav1k/1995-1837-0028.wav" controls style="width:200px;" preload></audio> | <audio src="samples/resyn/uniwav1k/61-70968-0026.wav" controls style="width:200px;" preload></audio> |

### <center> In-context Text-to-Speech </center>
<center> Samples are randomly selected from LibriSpeech test-clean subset. First 3 seconds of the ground truth are used as audio prompt. </center>

| <span style="width:1000px;">Text</span> | UniWav | Ground Truth |
| :---: | :---: | :---: |
| on arriving at home at my own residence i found that our salon was filled with a brilliant company | <audio src="samples/tts/uniwav/8455-210777-0002.wav" controls style="width:200px;" preload></audio> | <audio src="samples/tts/gt/8455-210777-0002.wav" controls style="width:200px;" preload></audio> |
| at the inception of plural marriage among the latter day saints there was no law national or state against its practise | <audio src="samples/tts/uniwav/4077-13754-0009.wav" controls style="width:200px;" preload></audio> | <audio src="samples/tts/gt/4077-13754-0009.wav" controls style="width:200px;" preload></audio> |
| we are losing time and the fact is i have not come all this way to take a little sail upon a pond on a raft | <audio src="samples/tts/uniwav/260-123286-0006.wav" controls style="width:200px;" preload></audio> | <audio src="samples/tts/gt/260-123286-0006.wav" controls style="width:200px;" preload></audio> |
| it was the first great sorrow of his life it was not so much the loss of the cotton itself but the fantasy the hopes the dreams built around it | <audio src="samples/tts/uniwav/1995-1837-0001.wav" controls style="width:200px;" preload></audio> | <audio src="samples/tts/gt/1995-1837-0001.wav" controls style="width:200px;" preload></audio> |
| for some years it was not found feasible to operate motors on alternating current circuits and that reason was often urged against it seriously | <audio src="samples/tts/uniwav/2300-131720-0009.wav" controls style="width:200px;" preload></audio> | <audio src="samples/tts/gt/2300-131720-0009.wav" controls style="width:200px;" preload></audio> |