# CasparCG[2022-05-15 00:23:17.558] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220514235317.mp4\r\n
[2022-05-15 00:23:17.562] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515002317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 00:23:17.562] [info]    ffmpeg[ch1/20220514235317.mp4] Uninitialized.
[2022-05-15 00:23:17.562] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 00:23:17.563] [info]    ffmpeg[ch1/20220515002317.mp4] Initialized.
[2022-05-15 00:23:17.563] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 00:23:17.570] [info]    [ffmpeg] [libx264 @ 000002B194999B40] using SAR=1/1
[2022-05-15 00:23:17.570] [info]    
[2022-05-15 00:23:17.570] [info]    [ffmpeg] [libx264 @ 000002B194999B40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 00:23:17.570] [info]    
[2022-05-15 00:23:17.578] [info]    [ffmpeg] [libx264 @ 000002B194999B40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 00:23:17.578] [info]    
[2022-05-15 00:23:17.587] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5600] Pure channel mapping detected:
[2022-05-15 00:23:17.587] [info]    [ffmpeg]  0
[2022-05-15 00:23:17.587] [info]    [ffmpeg]  1
[2022-05-15 00:23:17.587] [info]    [ffmpeg] 
[2022-05-15 00:23:17.587] [info]    
[2022-05-15 00:23:17.597] [warning] ffmpeg[ch1/20220515002317.mp4] Unused option s=1920:1080
[2022-05-15 00:23:17.669] [info]    [ffmpeg] [aac @ 000002B15E8763C0] Qavg: 232.814
[2022-05-15 00:23:17.669] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] frame I:360   Avg QP:23.86  size:113055
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] frame P:22816 Avg QP:13.04  size: 65633
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] frame B:66824 Avg QP:18.19  size:  8827
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] consecutive B-frames:  0.8%  0.7%  0.1% 98.4%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] mb I  I16..4: 50.4% 11.4% 38.1%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] mb P  I16..4:  3.5%  0.9%  1.1%  P16..4: 25.4%  4.3%  4.6%  0.0%  0.0%    skip:60.2%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.7%  2.0%  0.4%  direct: 4.7%  skip:87.9%  L0:43.1% L1:37.5% BI:19.4%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] 8x8 transform intra:18.2% inter:22.1%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] coded y,uvDC,uvAC intra: 53.6% 60.9% 50.8% inter: 8.7% 5.9% 2.5%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.679] [info]    [ffmpeg] [libx264 @ 000002B254984300] i16 v,h,dc,p: 61% 27%  8%  4%
[2022-05-15 00:23:17.679] [info]    
[2022-05-15 00:23:17.680] [info]    [ffmpeg] [libx264 @ 000002B254984300] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 18% 29% 28%  4%  3%  3%  4%  4%  6%
[2022-05-15 00:23:17.680] [info]    
[2022-05-15 00:23:17.680] [info]    [ffmpeg] [libx264 @ 000002B254984300] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 32% 10%  4%  5%  5%  6%  5%  6%
[2022-05-15 00:23:17.680] [info]    
[2022-05-15 00:23:17.680] [info]    [ffmpeg] [libx264 @ 000002B254984300] i8c dc,h,v,p: 48% 28% 20%  4%
[2022-05-15 00:23:17.680] [info]    
[2022-05-15 00:23:17.680] [info]    [ffmpeg] [libx264 @ 000002B254984300] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 00:23:17.680] [info]    
[2022-05-15 00:23:17.680] [info]    [ffmpeg] [libx264 @ 000002B254984300] kb/s:9458.01
[2022-05-15 00:23:17.680] [info]    
[2022-05-15 00:23:17.835] [info]    ffmpeg[ch1/20220514235317.mp4] Uninitialized.
[2022-05-15 00:23:47.560] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220514235347.mp4\r\n
[2022-05-15 00:23:47.562] [info]    ffmpeg[ch2/20220514235347.mp4] Uninitialized.
[2022-05-15 00:23:47.562] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 00:23:47.564] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515002347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 00:23:47.564] [info]    ffmpeg[ch2/20220515002347.mp4] Initialized.
[2022-05-15 00:23:47.564] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 00:23:47.570] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] using SAR=1/1
[2022-05-15 00:23:47.570] [info]    
[2022-05-15 00:23:47.571] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 00:23:47.571] [info]    
[2022-05-15 00:23:47.580] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 00:23:47.580] [info]    
[2022-05-15 00:23:47.599] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4A00] Pure channel mapping detected:
[2022-05-15 00:23:47.599] [info]    [ffmpeg]  0
[2022-05-15 00:23:47.599] [info]    [ffmpeg]  1
[2022-05-15 00:23:47.599] [info]    [ffmpeg] 
[2022-05-15 00:23:47.599] [info]    
[2022-05-15 00:23:47.601] [warning] ffmpeg[ch2/20220515002347.mp4] Unused option s=1920:1080
[2022-05-15 00:23:47.712] [info]    [ffmpeg] [aac @ 000002B1A6A23080] Qavg: 620.458
[2022-05-15 00:23:47.712] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] frame I:373   Avg QP:23.35  size:108259
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] frame P:23145 Avg QP:16.31  size: 62875
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] frame B:66482 Avg QP:19.11  size: 11015
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] consecutive B-frames:  0.9%  1.8%  0.5% 96.9%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] mb I  I16..4: 32.3% 36.1% 31.6%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] mb P  I16..4:  8.3%  9.5%  2.6%  P16..4: 32.7% 12.5%  8.9%  0.0%  0.0%    skip:25.5%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] mb B  I16..4:  1.1%  0.9%  0.1%  B16..8: 14.7%  4.6%  0.5%  direct:10.0%  skip:68.1%  L0:37.0% L1:49.7% BI:13.3%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] 8x8 transform intra:45.7% inter:26.9%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] coded y,uvDC,uvAC intra: 59.6% 63.2% 35.2% inter: 11.7% 12.4% 1.0%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] i16 v,h,dc,p: 45% 25% 21%  8%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 17% 26%  4%  7%  8%  6%  5%  4%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 21% 16%  5%  8%  8%  6%  5%  4%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] i8c dc,h,v,p: 47% 24% 23%  5%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] Weighted P-Frames: Y:0.4% UV:0.1%
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.720] [info]    [ffmpeg] [libx264 @ 000002B1A6928A00] kb/s:9901.97
[2022-05-15 00:23:47.720] [info]    
[2022-05-15 00:23:47.885] [info]    ffmpeg[ch2/20220514235347.mp4] Uninitialized.
[2022-05-15 00:53:17.587] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515002317.mp4\r\n
[2022-05-15 00:53:17.589] [info]    ffmpeg[ch1/20220515002317.mp4] Uninitialized.
[2022-05-15 00:53:17.590] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 00:53:17.592] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515005317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 00:53:17.593] [info]    ffmpeg[ch1/20220515005317.mp4] Initialized.
[2022-05-15 00:53:17.593] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 00:53:17.605] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] using SAR=1/1
[2022-05-15 00:53:17.605] [info]    
[2022-05-15 00:53:17.606] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 00:53:17.606] [info]    
[2022-05-15 00:53:17.614] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 00:53:17.614] [info]    
[2022-05-15 00:53:17.624] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0B40] Pure channel mapping detected:
[2022-05-15 00:53:17.625] [info]    [ffmpeg]  0
[2022-05-15 00:53:17.625] [info]    [ffmpeg]  1
[2022-05-15 00:53:17.625] [info]    [ffmpeg] 
[2022-05-15 00:53:17.625] [info]    
[2022-05-15 00:53:17.631] [warning] ffmpeg[ch1/20220515005317.mp4] Unused option s=1920:1080
[2022-05-15 00:53:17.677] [info]    [ffmpeg] [aac @ 000002B1FEC4BE80] Qavg: 7240.317
[2022-05-15 00:53:17.677] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] frame I:361   Avg QP:24.88  size:112027
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] frame P:22748 Avg QP:12.56  size: 67256
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] frame B:66892 Avg QP:17.72  size:  8714
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] consecutive B-frames:  0.8%  0.3%  0.1% 98.8%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] mb I  I16..4: 51.2% 10.9% 37.9%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] mb P  I16..4:  3.4%  0.6%  1.0%  P16..4: 27.5%  3.7%  4.0%  0.0%  0.0%    skip:59.7%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.4%  1.8%  0.4%  direct: 4.6%  skip:88.6%  L0:41.3% L1:42.6% BI:16.1%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] 8x8 transform intra:14.0% inter:21.2%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] coded y,uvDC,uvAC intra: 47.4% 58.0% 48.3% inter: 8.5% 6.3% 3.1%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] i16 v,h,dc,p: 64% 28%  4%  4%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 24% 24%  5%  4%  5%  5%  5%  6%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 29% 10%  4%  6%  6%  6%  4%  5%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] i8c dc,h,v,p: 46% 27% 23%  4%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.685] [info]    [ffmpeg] [libx264 @ 000002B194999B40] kb/s:9570.05
[2022-05-15 00:53:17.685] [info]    
[2022-05-15 00:53:17.836] [info]    ffmpeg[ch1/20220515002317.mp4] Uninitialized.
[2022-05-15 00:53:47.561] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515002347.mp4\r\n
[2022-05-15 00:53:47.562] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 00:53:47.562] [info]    ffmpeg[ch2/20220515002347.mp4] Uninitialized.
[2022-05-15 00:53:47.565] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515005347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 00:53:47.565] [info]    ffmpeg[ch2/20220515005347.mp4] Initialized.
[2022-05-15 00:53:47.565] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 00:53:47.571] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] using SAR=1/1
[2022-05-15 00:53:47.571] [info]    
[2022-05-15 00:53:47.571] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 00:53:47.571] [info]    
[2022-05-15 00:53:47.579] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 00:53:47.579] [info]    
[2022-05-15 00:53:47.611] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1940] Pure channel mapping detected:
[2022-05-15 00:53:47.611] [info]    [ffmpeg]  0
[2022-05-15 00:53:47.611] [info]    [ffmpeg]  1
[2022-05-15 00:53:47.611] [info]    [ffmpeg] 
[2022-05-15 00:53:47.611] [info]    
[2022-05-15 00:53:47.613] [warning] ffmpeg[ch2/20220515005347.mp4] Unused option s=1920:1080
[2022-05-15 00:53:47.696] [info]    [ffmpeg] [aac @ 000002B1954FE100] Qavg: 423.253
[2022-05-15 00:53:47.696] [info]    
[2022-05-15 00:53:47.704] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] frame I:377   Avg QP:22.34  size:103145
[2022-05-15 00:53:47.704] [info]    
[2022-05-15 00:53:47.704] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] frame P:23401 Avg QP:17.71  size: 59991
[2022-05-15 00:53:47.704] [info]    
[2022-05-15 00:53:47.704] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] frame B:66222 Avg QP:20.65  size: 10894
[2022-05-15 00:53:47.704] [info]    
[2022-05-15 00:53:47.704] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] consecutive B-frames:  1.1%  2.3%  0.7% 96.0%
[2022-05-15 00:53:47.704] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] mb I  I16..4: 26.3% 43.2% 30.5%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] mb P  I16..4: 11.0% 13.9%  3.1%  P16..4: 30.4% 14.1%  8.9%  0.0%  0.0%    skip:18.6%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] mb B  I16..4:  1.7%  1.2%  0.1%  B16..8: 16.4%  5.1%  0.4%  direct:10.7%  skip:64.4%  L0:45.6% L1:41.1% BI:13.3%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] 8x8 transform intra:47.4% inter:30.8%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] coded y,uvDC,uvAC intra: 52.9% 53.5% 19.4% inter: 11.9% 12.5% 0.5%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] i16 v,h,dc,p: 43% 28% 19%  9%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 22% 25%  4%  5%  6%  5%  5%  5%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 24% 14%  5%  7%  7%  6%  5%  4%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] i8c dc,h,v,p: 50% 24% 20%  6%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] Weighted P-Frames: Y:0.9% UV:0.1%
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.705] [info]    [ffmpeg] [libx264 @ 000002B15E932F40] kb/s:9618.36
[2022-05-15 00:53:47.705] [info]    
[2022-05-15 00:53:47.859] [info]    ffmpeg[ch2/20220515002347.mp4] Uninitialized.
[2022-05-15 01:23:17.589] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515005317.mp4\r\n
[2022-05-15 01:23:17.590] [info]    ffmpeg[ch1/20220515005317.mp4] Uninitialized.
[2022-05-15 01:23:17.590] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 01:23:17.592] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515012317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 01:23:17.593] [info]    ffmpeg[ch1/20220515012317.mp4] Initialized.
[2022-05-15 01:23:17.593] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 01:23:17.605] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] using SAR=1/1
[2022-05-15 01:23:17.605] [info]    
[2022-05-15 01:23:17.605] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 01:23:17.605] [info]    
[2022-05-15 01:23:17.609] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 01:23:17.609] [info]    
[2022-05-15 01:23:17.617] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1A40] Pure channel mapping detected:
[2022-05-15 01:23:17.617] [info]    [ffmpeg]  0
[2022-05-15 01:23:17.617] [info]    [ffmpeg]  1
[2022-05-15 01:23:17.617] [info]    [ffmpeg] 
[2022-05-15 01:23:17.617] [info]    
[2022-05-15 01:23:17.628] [warning] ffmpeg[ch1/20220515012317.mp4] Unused option s=1920:1080
[2022-05-15 01:23:17.699] [info]    [ffmpeg] [aac @ 000002B137BF0780] Qavg: 1007.143
[2022-05-15 01:23:17.699] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] frame I:360   Avg QP:25.35  size:112952
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] frame P:22718 Avg QP:12.20  size: 69494
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] frame B:66922 Avg QP:17.44  size:  9295
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] consecutive B-frames:  0.8%  0.2%  0.0% 99.0%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] mb I  I16..4: 51.4% 10.4% 38.2%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] mb P  I16..4:  3.6%  0.6%  0.7%  P16..4: 28.7%  3.4%  3.9%  0.0%  0.0%    skip:59.2%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.2%  1.7%  0.4%  direct: 4.8%  skip:88.6%  L0:38.8% L1:45.0% BI:16.2%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] 8x8 transform intra:12.4% inter:21.1%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] coded y,uvDC,uvAC intra: 45.2% 55.8% 48.1% inter: 8.8% 6.6% 3.4%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] i16 v,h,dc,p: 65% 28%  6%  2%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 24% 30%  4%  4%  4%  4%  4%  5%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 30% 10%  4%  5%  5%  5%  4%  5%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] i8c dc,h,v,p: 48% 26% 22%  3%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B2546B1C00] kb/s:9962.15
[2022-05-15 01:23:17.706] [info]    
[2022-05-15 01:23:17.849] [info]    ffmpeg[ch1/20220515005317.mp4] Uninitialized.
[2022-05-15 01:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515005347.mp4\r\n
[2022-05-15 01:23:47.559] [info]    ffmpeg[ch2/20220515005347.mp4] Uninitialized.
[2022-05-15 01:23:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 01:23:47.562] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515012347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 01:23:47.562] [info]    ffmpeg[ch2/20220515012347.mp4] Initialized.
[2022-05-15 01:23:47.563] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 01:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] using SAR=1/1
[2022-05-15 01:23:47.568] [info]    
[2022-05-15 01:23:47.569] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 01:23:47.569] [info]    
[2022-05-15 01:23:47.574] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 01:23:47.574] [info]    
[2022-05-15 01:23:47.582] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4E00] Pure channel mapping detected:
[2022-05-15 01:23:47.582] [info]    [ffmpeg]  0
[2022-05-15 01:23:47.582] [info]    [ffmpeg]  1
[2022-05-15 01:23:47.583] [info]    [ffmpeg] 
[2022-05-15 01:23:47.583] [info]    
[2022-05-15 01:23:47.588] [warning] ffmpeg[ch2/20220515012347.mp4] Unused option s=1920:1080
[2022-05-15 01:23:47.706] [info]    [ffmpeg] [aac @ 000002B15E6E71C0] Qavg: 743.848
[2022-05-15 01:23:47.706] [info]    
[2022-05-15 01:23:47.714] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] frame I:417   Avg QP:23.85  size:106490
[2022-05-15 01:23:47.714] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] frame P:23621 Avg QP:18.12  size: 62458
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] frame B:65962 Avg QP:21.83  size: 10108
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] consecutive B-frames:  1.0%  3.4%  0.8% 94.7%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] mb I  I16..4: 26.7% 41.5% 31.8%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] mb P  I16..4:  9.1% 12.1%  3.8%  P16..4: 28.1% 13.0%  8.5%  0.0%  0.0%    skip:25.4%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] mb B  I16..4:  1.1%  1.1%  0.1%  B16..8: 14.6%  4.5%  0.5%  direct: 8.8%  skip:69.3%  L0:47.0% L1:39.0% BI:14.0%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] 8x8 transform intra:47.5% inter:26.4%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] coded y,uvDC,uvAC intra: 56.6% 58.8% 25.9% inter: 10.7% 11.8% 0.8%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] i16 v,h,dc,p: 47% 26% 18%  9%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 20% 21%  4%  7%  8%  6%  5%  5%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 21% 13%  5%  8%  8%  7%  5%  5%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] i8c dc,h,v,p: 48% 23% 23%  6%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] Weighted P-Frames: Y:0.4% UV:0.1%
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.715] [info]    [ffmpeg] [libx264 @ 000002B1A67929C0] kb/s:9717.58
[2022-05-15 01:23:47.715] [info]    
[2022-05-15 01:23:47.869] [info]    ffmpeg[ch2/20220515005347.mp4] Uninitialized.
[2022-05-15 01:53:17.600] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515012317.mp4\r\n
[2022-05-15 01:53:17.601] [info]    ffmpeg[ch1/20220515012317.mp4] Uninitialized.
[2022-05-15 01:53:17.601] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 01:53:17.602] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515015317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 01:53:17.602] [info]    ffmpeg[ch1/20220515015317.mp4] Initialized.
[2022-05-15 01:53:17.603] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 01:53:17.610] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] using SAR=1/1
[2022-05-15 01:53:17.610] [info]    
[2022-05-15 01:53:17.611] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 01:53:17.611] [info]    
[2022-05-15 01:53:17.621] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 01:53:17.621] [info]    
[2022-05-15 01:53:17.650] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4A00] Pure channel mapping detected:
[2022-05-15 01:53:17.650] [info]    [ffmpeg]  0
[2022-05-15 01:53:17.650] [info]    [ffmpeg]  1
[2022-05-15 01:53:17.650] [info]    [ffmpeg] 
[2022-05-15 01:53:17.650] [info]    
[2022-05-15 01:53:17.657] [warning] ffmpeg[ch1/20220515015317.mp4] Unused option s=1920:1080
[2022-05-15 01:53:17.681] [info]    [ffmpeg] [aac @ 000002B1FEF522C0] Qavg: 7885.619
[2022-05-15 01:53:17.681] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] frame I:360   Avg QP:25.47  size:111067
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] frame P:22787 Avg QP:13.78  size: 67136
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] frame B:66853 Avg QP:19.29  size:  8938
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] consecutive B-frames:  0.8%  0.5%  0.2% 98.5%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] mb I  I16..4: 48.8% 12.8% 38.4%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] mb P  I16..4:  3.5%  0.9%  1.3%  P16..4: 26.7%  4.4%  4.6%  0.0%  0.0%    skip:58.4%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.8%  2.1%  0.5%  direct: 4.8%  skip:87.4%  L0:40.9% L1:40.9% BI:18.2%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] 8x8 transform intra:17.7% inter:21.6%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] coded y,uvDC,uvAC intra: 50.1% 58.0% 45.1% inter: 8.9% 6.5% 2.8%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] i16 v,h,dc,p: 62% 29%  5%  4%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 29% 20%  4%  5%  5%  6%  5%  6%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] i8c dc,h,v,p: 46% 26% 22%  5%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.686] [info]    [ffmpeg] [libx264 @ 000002B1A6CE05C0] kb/s:9632.69
[2022-05-15 01:53:17.686] [info]    
[2022-05-15 01:53:17.831] [info]    ffmpeg[ch1/20220515012317.mp4] Uninitialized.
[2022-05-15 01:53:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515012347.mp4\r\n
[2022-05-15 01:53:47.560] [info]    ffmpeg[ch2/20220515012347.mp4] Uninitialized.
[2022-05-15 01:53:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 01:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515015347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 01:53:47.562] [info]    ffmpeg[ch2/20220515015347.mp4] Initialized.
[2022-05-15 01:53:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 01:53:47.569] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] using SAR=1/1
[2022-05-15 01:53:47.569] [info]    
[2022-05-15 01:53:47.569] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 01:53:47.569] [info]    
[2022-05-15 01:53:47.574] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 01:53:47.574] [info]    
[2022-05-15 01:53:47.581] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0240] Pure channel mapping detected:
[2022-05-15 01:53:47.582] [info]    [ffmpeg]  0
[2022-05-15 01:53:47.582] [info]    [ffmpeg]  1
[2022-05-15 01:53:47.582] [info]    [ffmpeg] 
[2022-05-15 01:53:47.582] [info]    
[2022-05-15 01:53:47.587] [warning] ffmpeg[ch2/20220515015347.mp4] Unused option s=1920:1080
[2022-05-15 01:53:47.688] [info]    [ffmpeg] [aac @ 000002B254F1D500] Qavg: 401.325
[2022-05-15 01:53:47.688] [info]    
[2022-05-15 01:53:47.694] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] frame I:378   Avg QP:23.75  size:108264
[2022-05-15 01:53:47.694] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] frame P:23007 Avg QP:17.08  size: 62582
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] frame B:66615 Avg QP:19.98  size: 10827
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] consecutive B-frames:  0.8%  1.3%  0.3% 97.5%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] mb I  I16..4: 30.8% 36.9% 32.3%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] mb P  I16..4:  8.2%  8.8%  2.0%  P16..4: 33.9% 13.0%  9.4%  0.0%  0.0%    skip:24.6%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] mb B  I16..4:  1.1%  0.7%  0.1%  B16..8: 14.4%  4.6%  0.5%  direct:10.1%  skip:68.6%  L0:47.3% L1:37.9% BI:14.8%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] 8x8 transform intra:44.3% inter:27.4%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] coded y,uvDC,uvAC intra: 58.1% 64.8% 35.2% inter: 11.9% 12.7% 1.0%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] i16 v,h,dc,p: 43% 26% 22%  8%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 19% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 16%  5%  7%  7%  6%  6%  5%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] i8c dc,h,v,p: 46% 25% 22%  6%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] Weighted P-Frames: Y:0.4% UV:0.2%
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B1FEB53DC0] kb/s:9786.60
[2022-05-15 01:53:47.695] [info]    
[2022-05-15 01:53:47.850] [info]    ffmpeg[ch2/20220515012347.mp4] Uninitialized.
[2022-05-15 02:05:11.449] [warning] DeckLink Duo 2 [3|1080i5000] out-sync changed: 0.02
[2022-05-15 02:05:11.486] [warning] DeckLink Duo 2 [3|1080i5000] out-sync changed: 0.04
[2022-05-15 02:23:17.589] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515015317.mp4\r\n
[2022-05-15 02:23:17.591] [info]    ffmpeg[ch1/20220515015317.mp4] Uninitialized.
[2022-05-15 02:23:17.591] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 02:23:17.593] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515022317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 02:23:17.595] [info]    ffmpeg[ch1/20220515022317.mp4] Initialized.
[2022-05-15 02:23:17.595] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 02:23:17.602] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] using SAR=1/1
[2022-05-15 02:23:17.602] [info]    
[2022-05-15 02:23:17.603] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 02:23:17.603] [info]    
[2022-05-15 02:23:17.608] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 02:23:17.608] [info]    
[2022-05-15 02:23:17.617] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0740] Pure channel mapping detected:
[2022-05-15 02:23:17.617] [info]    [ffmpeg]  0
[2022-05-15 02:23:17.617] [info]    [ffmpeg]  1
[2022-05-15 02:23:17.617] [info]    [ffmpeg] 
[2022-05-15 02:23:17.617] [info]    
[2022-05-15 02:23:17.624] [warning] ffmpeg[ch1/20220515022317.mp4] Unused option s=1920:1080
[2022-05-15 02:23:17.689] [info]    [ffmpeg] [aac @ 000002B1FB889FC0] Qavg: 1316.525
[2022-05-15 02:23:17.689] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] frame I:360   Avg QP:25.63  size:110887
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] frame P:22779 Avg QP:13.49  size: 68071
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] frame B:66861 Avg QP:19.09  size:  8523
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] consecutive B-frames:  0.8%  0.5%  0.2% 98.6%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] mb I  I16..4: 48.9% 13.0% 38.1%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] mb P  I16..4:  3.1%  0.5%  0.7%  P16..4: 28.1%  4.2%  4.7%  0.0%  0.0%    skip:58.7%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.2%  1.7%  0.4%  direct: 4.8%  skip:88.6%  L0:37.8% L1:42.9% BI:19.4%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] 8x8 transform intra:13.7% inter:21.6%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.698] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] coded y,uvDC,uvAC intra: 43.5% 55.5% 45.2% inter: 9.0% 6.4% 3.0%
[2022-05-15 02:23:17.698] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] i16 v,h,dc,p: 68% 26%  4%  3%
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 28% 23%  4%  4%  4%  6%  4%  7%
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 31% 10%  4%  5%  5%  6%  4%  5%
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] i8c dc,h,v,p: 49% 25% 22%  4%
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.699] [info]    [ffmpeg] [libx264 @ 000002B1FF375900] kb/s:9601.54
[2022-05-15 02:23:17.699] [info]    
[2022-05-15 02:23:17.844] [info]    ffmpeg[ch1/20220515015317.mp4] Uninitialized.
[2022-05-15 02:23:47.563] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515015347.mp4\r\n
[2022-05-15 02:23:47.564] [info]    ffmpeg[ch2/20220515015347.mp4] Uninitialized.
[2022-05-15 02:23:47.564] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 02:23:47.565] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515022347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 02:23:47.566] [info]    ffmpeg[ch2/20220515022347.mp4] Initialized.
[2022-05-15 02:23:47.566] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 02:23:47.575] [info]    [ffmpeg] [libx264 @ 000002B15E926740] using SAR=1/1
[2022-05-15 02:23:47.575] [info]    
[2022-05-15 02:23:47.576] [info]    [ffmpeg] [libx264 @ 000002B15E926740] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 02:23:47.576] [info]    
[2022-05-15 02:23:47.582] [info]    [ffmpeg] [libx264 @ 000002B15E926740] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 02:23:47.582] [info]    
[2022-05-15 02:23:47.594] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1840] Pure channel mapping detected:
[2022-05-15 02:23:47.594] [info]    [ffmpeg]  0
[2022-05-15 02:23:47.594] [info]    [ffmpeg]  1
[2022-05-15 02:23:47.594] [info]    [ffmpeg] 
[2022-05-15 02:23:47.594] [info]    
[2022-05-15 02:23:47.602] [warning] ffmpeg[ch2/20220515022347.mp4] Unused option s=1920:1080
[2022-05-15 02:23:47.661] [info]    [ffmpeg] [aac @ 000002B1FEB9E400] Qavg: 371.374
[2022-05-15 02:23:47.661] [info]    
[2022-05-15 02:23:47.668] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] frame I:367   Avg QP:23.91  size:109142
[2022-05-15 02:23:47.668] [info]    
[2022-05-15 02:23:47.668] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] frame P:23223 Avg QP:16.49  size: 63448
[2022-05-15 02:23:47.668] [info]    
[2022-05-15 02:23:47.668] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] frame B:66410 Avg QP:19.26  size: 10928
[2022-05-15 02:23:47.668] [info]    
[2022-05-15 02:23:47.668] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] consecutive B-frames:  0.8%  2.2%  0.4% 96.6%
[2022-05-15 02:23:47.668] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] mb I  I16..4: 32.0% 35.3% 32.6%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] mb P  I16..4:  7.3%  7.9%  2.1%  P16..4: 34.2% 13.1%  9.6%  0.0%  0.0%    skip:25.8%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] mb B  I16..4:  0.9%  0.7%  0.1%  B16..8: 14.6%  4.5%  0.5%  direct:10.0%  skip:68.8%  L0:34.5% L1:51.7% BI:13.8%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] 8x8 transform intra:44.1% inter:27.2%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] coded y,uvDC,uvAC intra: 59.6% 68.3% 40.4% inter: 12.1% 12.5% 1.1%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] i16 v,h,dc,p: 45% 26% 21%  8%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 19% 27%  4%  6%  7%  6%  5%  5%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 23% 15%  5%  7%  7%  6%  5%  5%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] i8c dc,h,v,p: 45% 26% 22%  6%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] Weighted P-Frames: Y:0.1% UV:0.0%
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.669] [info]    [ffmpeg] [libx264 @ 000002B137F2B780] kb/s:9952.26
[2022-05-15 02:23:47.669] [info]    
[2022-05-15 02:23:47.815] [info]    ffmpeg[ch2/20220515015347.mp4] Uninitialized.
[2022-05-15 02:53:17.603] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515022317.mp4\r\n
[2022-05-15 02:53:17.603] [info]    ffmpeg[ch1/20220515022317.mp4] Uninitialized.
[2022-05-15 02:53:17.603] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 02:53:17.605] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515025317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 02:53:17.605] [info]    ffmpeg[ch1/20220515025317.mp4] Initialized.
[2022-05-15 02:53:17.605] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 02:53:17.610] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] using SAR=1/1
[2022-05-15 02:53:17.610] [info]    
[2022-05-15 02:53:17.611] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 02:53:17.611] [info]    
[2022-05-15 02:53:17.622] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 02:53:17.622] [info]    
[2022-05-15 02:53:17.634] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4A00] Pure channel mapping detected:
[2022-05-15 02:53:17.634] [info]    [ffmpeg]  0
[2022-05-15 02:53:17.634] [info]    [ffmpeg]  1
[2022-05-15 02:53:17.634] [info]    [ffmpeg] 
[2022-05-15 02:53:17.634] [info]    
[2022-05-15 02:53:17.643] [warning] ffmpeg[ch1/20220515025317.mp4] Unused option s=1920:1080
[2022-05-15 02:53:17.688] [info]    [ffmpeg] [aac @ 000002B255527CC0] Qavg: 2927.050
[2022-05-15 02:53:17.688] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] frame I:360   Avg QP:26.13  size:111898
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] frame P:22785 Avg QP:13.85  size: 68301
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] frame B:66855 Avg QP:19.59  size:  9268
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] consecutive B-frames:  0.8%  0.6%  0.1% 98.5%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] mb I  I16..4: 48.2% 13.3% 38.6%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] mb P  I16..4:  3.5%  0.9%  1.4%  P16..4: 26.8%  4.9%  5.0%  0.0%  0.0%    skip:57.6%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  4.8%  2.0%  0.5%  direct: 4.8%  skip:87.4%  L0:39.7% L1:41.9% BI:18.4%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] 8x8 transform intra:17.1% inter:21.8%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] coded y,uvDC,uvAC intra: 50.2% 58.6% 44.8% inter: 9.0% 6.5% 2.7%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] i16 v,h,dc,p: 62% 28%  5%  5%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 27% 20%  5%  5%  5%  6%  5%  6%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 29%  9%  4%  6%  6%  6%  4%  5%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] i8c dc,h,v,p: 46% 26% 23%  5%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.696] [info]    [ffmpeg] [libx264 @ 000002B2554A8300] kb/s:9849.37
[2022-05-15 02:53:17.696] [info]    
[2022-05-15 02:53:17.844] [info]    ffmpeg[ch1/20220515022317.mp4] Uninitialized.
[2022-05-15 02:53:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515022347.mp4\r\n
[2022-05-15 02:53:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 02:53:47.560] [info]    ffmpeg[ch2/20220515022347.mp4] Uninitialized.
[2022-05-15 02:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515025347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 02:53:47.562] [info]    ffmpeg[ch2/20220515025347.mp4] Initialized.
[2022-05-15 02:53:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 02:53:47.567] [info]    [ffmpeg] [libx264 @ 000002B137E03280] using SAR=1/1
[2022-05-15 02:53:47.567] [info]    
[2022-05-15 02:53:47.568] [info]    [ffmpeg] [libx264 @ 000002B137E03280] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 02:53:47.568] [info]    
[2022-05-15 02:53:47.575] [info]    [ffmpeg] [libx264 @ 000002B137E03280] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 02:53:47.575] [info]    
[2022-05-15 02:53:47.584] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5700] Pure channel mapping detected:
[2022-05-15 02:53:47.584] [info]    [ffmpeg]  0
[2022-05-15 02:53:47.584] [info]    [ffmpeg]  1
[2022-05-15 02:53:47.584] [info]    [ffmpeg] 
[2022-05-15 02:53:47.584] [info]    
[2022-05-15 02:53:47.591] [warning] ffmpeg[ch2/20220515025347.mp4] Unused option s=1920:1080
[2022-05-15 02:53:47.713] [info]    [ffmpeg] [aac @ 000002B15E8B1E40] Qavg: 507.245
[2022-05-15 02:53:47.713] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] frame I:376   Avg QP:20.79  size:100749
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] frame P:23633 Avg QP:17.36  size: 58700
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] frame B:65991 Avg QP:21.02  size: 10591
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] consecutive B-frames:  0.9%  3.7%  0.8% 94.5%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] mb I  I16..4: 33.9% 38.8% 27.3%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] mb P  I16..4: 16.0% 14.6%  3.9%  P16..4: 25.9% 10.9%  6.8%  0.0%  0.0%    skip:21.9%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] mb B  I16..4:  1.9%  1.4%  0.1%  B16..8: 15.1%  4.4%  0.4%  direct: 9.5%  skip:67.3%  L0:43.2% L1:45.1% BI:11.7%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] 8x8 transform intra:41.8% inter:27.8%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] coded y,uvDC,uvAC intra: 49.4% 54.5% 22.7% inter: 9.8% 12.6% 0.7%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] i16 v,h,dc,p: 51% 25% 16%  7%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 22% 26%  4%  5%  6%  5%  5%  4%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 23% 13%  5%  7%  8%  7%  6%  5%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] i8c dc,h,v,p: 49% 24% 20%  6%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] Weighted P-Frames: Y:0.7% UV:0.1%
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.722] [info]    [ffmpeg] [libx264 @ 000002B15E926740] kb/s:9440.29
[2022-05-15 02:53:47.722] [info]    
[2022-05-15 02:53:47.883] [info]    ffmpeg[ch2/20220515022347.mp4] Uninitialized.
[2022-05-15 03:23:17.598] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515025317.mp4\r\n
[2022-05-15 03:23:17.600] [info]    ffmpeg[ch1/20220515025317.mp4] Uninitialized.
[2022-05-15 03:23:17.600] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 03:23:17.602] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515032317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 03:23:17.603] [info]    ffmpeg[ch1/20220515032317.mp4] Initialized.
[2022-05-15 03:23:17.603] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 03:23:17.608] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] using SAR=1/1
[2022-05-15 03:23:17.608] [info]    
[2022-05-15 03:23:17.608] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 03:23:17.608] [info]    
[2022-05-15 03:23:17.614] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 03:23:17.614] [info]    
[2022-05-15 03:23:17.625] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0F40] Pure channel mapping detected:
[2022-05-15 03:23:17.625] [info]    [ffmpeg]  0
[2022-05-15 03:23:17.626] [info]    [ffmpeg]  1
[2022-05-15 03:23:17.626] [info]    [ffmpeg] 
[2022-05-15 03:23:17.626] [info]    
[2022-05-15 03:23:17.634] [warning] ffmpeg[ch1/20220515032317.mp4] Unused option s=1920:1080
[2022-05-15 03:23:17.696] [info]    [ffmpeg] [aac @ 000002B254A04080] Qavg: 6991.543
[2022-05-15 03:23:17.696] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] frame I:360   Avg QP:24.64  size:111426
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] frame P:22739 Avg QP:12.64  size: 67612
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] frame B:66901 Avg QP:17.75  size:  8400
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] consecutive B-frames:  0.8%  0.3%  0.1% 98.8%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] mb I  I16..4: 50.7% 12.0% 37.2%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] mb P  I16..4:  3.4%  0.6%  0.8%  P16..4: 27.9%  4.2%  4.2%  0.0%  0.0%    skip:58.9%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.5%  1.7%  0.4%  direct: 4.8%  skip:88.3%  L0:39.2% L1:44.3% BI:16.5%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] 8x8 transform intra:13.5% inter:22.5%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] coded y,uvDC,uvAC intra: 45.3% 57.1% 47.6% inter: 8.8% 6.5% 3.2%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] i16 v,h,dc,p: 65% 26%  5%  3%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 26% 26%  4%  4%  4%  4%  4%  5%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 33% 30%  9%  4%  5%  5%  5%  4%  4%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] i8c dc,h,v,p: 47% 26% 23%  5%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.706] [info]    [ffmpeg] [libx264 @ 000002B194F0BB40] kb/s:9508.94
[2022-05-15 03:23:17.706] [info]    
[2022-05-15 03:23:17.853] [info]    ffmpeg[ch1/20220515025317.mp4] Uninitialized.
[2022-05-15 03:23:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515025347.mp4\r\n
[2022-05-15 03:23:47.561] [info]    ffmpeg[ch2/20220515025347.mp4] Uninitialized.
[2022-05-15 03:23:47.561] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 03:23:47.564] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515032347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 03:23:47.564] [info]    ffmpeg[ch2/20220515032347.mp4] Initialized.
[2022-05-15 03:23:47.564] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 03:23:47.570] [info]    [ffmpeg] [libx264 @ 000002B195022440] using SAR=1/1
[2022-05-15 03:23:47.570] [info]    
[2022-05-15 03:23:47.570] [info]    [ffmpeg] [libx264 @ 000002B195022440] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 03:23:47.570] [info]    
[2022-05-15 03:23:47.576] [info]    [ffmpeg] [libx264 @ 000002B195022440] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 03:23:47.576] [info]    
[2022-05-15 03:23:47.599] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1940] Pure channel mapping detected:
[2022-05-15 03:23:47.599] [info]    [ffmpeg]  0
[2022-05-15 03:23:47.599] [info]    [ffmpeg]  1
[2022-05-15 03:23:47.599] [info]    [ffmpeg] 
[2022-05-15 03:23:47.599] [info]    
[2022-05-15 03:23:47.602] [warning] ffmpeg[ch2/20220515032347.mp4] Unused option s=1920:1080
[2022-05-15 03:23:47.706] [info]    [ffmpeg] [aac @ 000002B1FF375900] Qavg: 577.992
[2022-05-15 03:23:47.706] [info]    
[2022-05-15 03:23:47.718] [info]    [ffmpeg] [libx264 @ 000002B137E03280] frame I:379   Avg QP:22.67  size:103424
[2022-05-15 03:23:47.718] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] frame P:23470 Avg QP:18.15  size: 60846
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] frame B:66151 Avg QP:21.42  size: 10516
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] consecutive B-frames:  0.9%  2.9%  0.7% 95.4%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] mb I  I16..4: 27.6% 43.3% 29.1%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] mb P  I16..4: 11.5% 14.5%  3.3%  P16..4: 29.5% 12.4%  7.8%  0.0%  0.0%    skip:20.9%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] mb B  I16..4:  1.5%  1.3%  0.1%  B16..8: 15.2%  4.6%  0.4%  direct:10.1%  skip:66.8%  L0:46.5% L1:39.9% BI:13.6%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] 8x8 transform intra:48.0% inter:29.8%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] coded y,uvDC,uvAC intra: 55.4% 58.3% 22.9% inter: 10.9% 13.5% 0.6%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] i16 v,h,dc,p: 43% 27% 20% 10%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 21% 26%  4%  5%  6%  5%  5%  4%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 23% 13%  5%  7%  8%  6%  6%  5%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] i8c dc,h,v,p: 47% 25% 22%  6%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] Weighted P-Frames: Y:0.8% UV:0.2%
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.719] [info]    [ffmpeg] [libx264 @ 000002B137E03280] kb/s:9612.99
[2022-05-15 03:23:47.719] [info]    
[2022-05-15 03:23:47.888] [info]    ffmpeg[ch2/20220515025347.mp4] Uninitialized.
[2022-05-15 03:53:17.607] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515032317.mp4\r\n
[2022-05-15 03:53:17.607] [info]    ffmpeg[ch1/20220515032317.mp4] Uninitialized.
[2022-05-15 03:53:17.607] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 03:53:17.609] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515035317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 03:53:17.609] [info]    ffmpeg[ch1/20220515035317.mp4] Initialized.
[2022-05-15 03:53:17.609] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 03:53:17.617] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] using SAR=1/1
[2022-05-15 03:53:17.617] [info]    
[2022-05-15 03:53:17.618] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 03:53:17.618] [info]    
[2022-05-15 03:53:17.625] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 03:53:17.625] [info]    
[2022-05-15 03:53:17.650] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4F00] Pure channel mapping detected:
[2022-05-15 03:53:17.650] [info]    [ffmpeg]  0
[2022-05-15 03:53:17.650] [info]    [ffmpeg]  1
[2022-05-15 03:53:17.650] [info]    [ffmpeg] 
[2022-05-15 03:53:17.650] [info]    
[2022-05-15 03:53:17.660] [warning] ffmpeg[ch1/20220515035317.mp4] Unused option s=1920:1080
[2022-05-15 03:53:17.714] [info]    [ffmpeg] [aac @ 000002B195450BC0] Qavg: 5037.423
[2022-05-15 03:53:17.714] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] frame I:360   Avg QP:27.90  size:111303
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] frame P:22785 Avg QP:15.12  size: 68134
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] frame B:66855 Avg QP:21.23  size:  9202
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] consecutive B-frames:  0.7%  0.6%  0.2% 98.5%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] mb I  I16..4: 44.5% 15.1% 40.3%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] mb P  I16..4:  3.0%  0.9%  1.5%  P16..4: 27.1%  5.4%  5.7%  0.0%  0.0%    skip:56.3%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  4.9%  2.1%  0.6%  direct: 4.6%  skip:87.4%  L0:38.6% L1:41.8% BI:19.6%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] 8x8 transform intra:18.0% inter:21.3%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] coded y,uvDC,uvAC intra: 50.9% 60.3% 44.5% inter: 9.0% 6.6% 2.5%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] i16 v,h,dc,p: 60% 31%  3%  6%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 27% 17%  5%  5%  5%  7%  5%  6%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28%  9%  4%  6%  6%  6%  5%  5%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] i8c dc,h,v,p: 42% 28% 24%  6%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.726] [info]    [ffmpeg] [libx264 @ 000002B2552578C0] kb/s:9812.03
[2022-05-15 03:53:17.726] [info]    
[2022-05-15 03:53:17.884] [info]    ffmpeg[ch1/20220515032317.mp4] Uninitialized.
[2022-05-15 03:53:47.566] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515032347.mp4\r\n
[2022-05-15 03:53:47.567] [info]    ffmpeg[ch2/20220515032347.mp4] Uninitialized.
[2022-05-15 03:53:47.567] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 03:53:47.568] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515035347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 03:53:47.568] [info]    ffmpeg[ch2/20220515035347.mp4] Initialized.
[2022-05-15 03:53:47.568] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 03:53:47.575] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] using SAR=1/1
[2022-05-15 03:53:47.575] [info]    
[2022-05-15 03:53:47.576] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 03:53:47.576] [info]    
[2022-05-15 03:53:47.582] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 03:53:47.582] [info]    
[2022-05-15 03:53:47.595] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4B00] Pure channel mapping detected:
[2022-05-15 03:53:47.595] [info]    [ffmpeg]  0
[2022-05-15 03:53:47.595] [info]    [ffmpeg]  1
[2022-05-15 03:53:47.595] [info]    [ffmpeg] 
[2022-05-15 03:53:47.595] [info]    
[2022-05-15 03:53:47.602] [warning] ffmpeg[ch2/20220515035347.mp4] Unused option s=1920:1080
[2022-05-15 03:53:47.689] [info]    [ffmpeg] [aac @ 000002B255143100] Qavg: 509.075
[2022-05-15 03:53:47.689] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] frame I:374   Avg QP:23.00  size:104006
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] frame P:23238 Avg QP:17.15  size: 61076
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] frame B:66388 Avg QP:20.73  size: 10540
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] consecutive B-frames:  0.9%  2.0%  0.8% 96.3%
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] mb I  I16..4: 28.1% 40.6% 31.3%
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] mb P  I16..4:  8.2% 12.0%  3.2%  P16..4: 28.2% 10.8%  7.9%  0.0%  0.0%    skip:29.6%
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.695] [info]    [ffmpeg] [libx264 @ 000002B195022440] mb B  I16..4:  1.7%  1.7%  0.1%  B16..8: 12.7%  3.9%  0.5%  direct: 8.0%  skip:71.4%  L0:45.5% L1:40.2% BI:14.3%
[2022-05-15 03:53:47.695] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] 8x8 transform intra:49.9% inter:26.6%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] coded y,uvDC,uvAC intra: 63.2% 56.1% 22.2% inter: 10.2% 10.6% 0.7%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] i16 v,h,dc,p: 36% 26% 27% 12%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 19% 30%  4%  5%  6%  5%  5%  5%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 24% 14%  5%  7%  7%  7%  6%  5%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] i8c dc,h,v,p: 48% 25% 21%  5%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] Weighted P-Frames: Y:0.6% UV:0.1%
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.696] [info]    [ffmpeg] [libx264 @ 000002B195022440] kb/s:9590.68
[2022-05-15 03:53:47.696] [info]    
[2022-05-15 03:53:47.854] [info]    ffmpeg[ch2/20220515032347.mp4] Uninitialized.
[2022-05-15 04:23:17.615] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515035317.mp4\r\n
[2022-05-15 04:23:17.617] [info]    ffmpeg[ch1/20220515035317.mp4] Uninitialized.
[2022-05-15 04:23:17.617] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 04:23:17.619] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515042317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 04:23:17.620] [info]    ffmpeg[ch1/20220515042317.mp4] Initialized.
[2022-05-15 04:23:17.620] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 04:23:17.625] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] using SAR=1/1
[2022-05-15 04:23:17.625] [info]    
[2022-05-15 04:23:17.625] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 04:23:17.625] [info]    
[2022-05-15 04:23:17.633] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 04:23:17.633] [info]    
[2022-05-15 04:23:17.650] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0340] Pure channel mapping detected:
[2022-05-15 04:23:17.650] [info]    [ffmpeg]  0
[2022-05-15 04:23:17.650] [info]    [ffmpeg]  1
[2022-05-15 04:23:17.650] [info]    [ffmpeg] 
[2022-05-15 04:23:17.650] [info]    
[2022-05-15 04:23:17.655] [warning] ffmpeg[ch1/20220515042317.mp4] Unused option s=1920:1080
[2022-05-15 04:23:17.747] [info]    [ffmpeg] [aac @ 000002B1FF7A5F80] Qavg: 12451.305
[2022-05-15 04:23:17.747] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] frame I:361   Avg QP:27.66  size:114084
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] frame P:22794 Avg QP:15.25  size: 70219
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] frame B:66846 Avg QP:21.44  size:  9229
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] consecutive B-frames:  0.8%  0.6%  0.1% 98.5%
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] mb I  I16..4: 43.8% 14.9% 41.3%
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] mb P  I16..4:  2.6%  0.7%  1.2%  P16..4: 28.6%  5.3%  5.9%  0.0%  0.0%    skip:55.8%
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.7%  2.0%  0.6%  direct: 4.7%  skip:87.8%  L0:36.3% L1:42.9% BI:20.8%
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.755] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] 8x8 transform intra:15.8% inter:21.9%
[2022-05-15 04:23:17.755] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] coded y,uvDC,uvAC intra: 48.7% 58.5% 43.7% inter: 9.3% 6.6% 2.4%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] i16 v,h,dc,p: 62% 31%  3%  3%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 27% 17%  4%  5%  5%  6%  5%  6%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28%  9%  4%  6%  6%  6%  5%  5%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] i8c dc,h,v,p: 44% 28% 24%  4%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.756] [info]    [ffmpeg] [libx264 @ 000002B1FB12F000] kb/s:10038.50
[2022-05-15 04:23:17.756] [info]    
[2022-05-15 04:23:17.901] [info]    ffmpeg[ch1/20220515035317.mp4] Uninitialized.
[2022-05-15 04:23:47.561] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515035347.mp4\r\n
[2022-05-15 04:23:47.563] [info]    ffmpeg[ch2/20220515035347.mp4] Uninitialized.
[2022-05-15 04:23:47.563] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 04:23:47.567] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515042347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 04:23:47.568] [info]    ffmpeg[ch2/20220515042347.mp4] Initialized.
[2022-05-15 04:23:47.568] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 04:23:47.575] [info]    [ffmpeg] [libx264 @ 000002B254A04540] using SAR=1/1
[2022-05-15 04:23:47.575] [info]    
[2022-05-15 04:23:47.575] [info]    [ffmpeg] [libx264 @ 000002B254A04540] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 04:23:47.575] [info]    
[2022-05-15 04:23:47.582] [info]    [ffmpeg] [libx264 @ 000002B254A04540] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 04:23:47.582] [info]    
[2022-05-15 04:23:47.606] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1640] Pure channel mapping detected:
[2022-05-15 04:23:47.606] [info]    [ffmpeg]  0
[2022-05-15 04:23:47.606] [info]    [ffmpeg]  1
[2022-05-15 04:23:47.606] [info]    [ffmpeg] 
[2022-05-15 04:23:47.606] [info]    
[2022-05-15 04:23:47.609] [warning] ffmpeg[ch2/20220515042347.mp4] Unused option s=1920:1080
[2022-05-15 04:23:47.683] [info]    [ffmpeg] [aac @ 000002B25502D180] Qavg: 287.291
[2022-05-15 04:23:47.683] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] frame I:362   Avg QP:24.04  size:106208
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] frame P:23069 Avg QP:17.36  size: 62568
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] frame B:66569 Avg QP:20.65  size: 10188
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] consecutive B-frames:  0.9%  1.4%  0.6% 97.2%
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] mb I  I16..4: 29.1% 37.4% 33.5%
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] mb P  I16..4:  7.3% 10.6%  2.9%  P16..4: 29.8% 11.5%  8.7%  0.0%  0.0%    skip:29.3%
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] mb B  I16..4:  1.5%  1.3%  0.1%  B16..8: 13.3%  4.0%  0.4%  direct: 8.6%  skip:70.8%  L0:44.8% L1:40.4% BI:14.8%
[2022-05-15 04:23:47.689] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] 8x8 transform intra:48.6% inter:27.0%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] coded y,uvDC,uvAC intra: 63.2% 56.3% 21.9% inter: 10.9% 11.0% 0.6%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] i16 v,h,dc,p: 34% 27% 28% 11%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 17% 35%  4%  5%  6%  4%  5%  5%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 23% 15%  5%  7%  7%  6%  5%  5%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] i8c dc,h,v,p: 47% 26% 22%  5%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1FEA34E40] kb/s:9600.29
[2022-05-15 04:23:47.690] [info]    
[2022-05-15 04:23:47.845] [info]    ffmpeg[ch2/20220515035347.mp4] Uninitialized.
[2022-05-15 04:53:17.605] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515042317.mp4\r\n
[2022-05-15 04:53:17.606] [info]    ffmpeg[ch1/20220515042317.mp4] Uninitialized.
[2022-05-15 04:53:17.606] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 04:53:17.609] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515045317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 04:53:17.610] [info]    ffmpeg[ch1/20220515045317.mp4] Initialized.
[2022-05-15 04:53:17.610] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 04:53:17.630] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] using SAR=1/1
[2022-05-15 04:53:17.630] [info]    
[2022-05-15 04:53:17.630] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 04:53:17.630] [info]    
[2022-05-15 04:53:17.643] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 04:53:17.643] [info]    
[2022-05-15 04:53:17.659] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5600] Pure channel mapping detected:
[2022-05-15 04:53:17.659] [info]    [ffmpeg]  0
[2022-05-15 04:53:17.659] [info]    [ffmpeg]  1
[2022-05-15 04:53:17.659] [info]    [ffmpeg] 
[2022-05-15 04:53:17.659] [info]    
[2022-05-15 04:53:17.661] [warning] ffmpeg[ch1/20220515045317.mp4] Unused option s=1920:1080
[2022-05-15 04:53:17.709] [info]    [ffmpeg] [aac @ 000002B137F9D8C0] Qavg: 12227.356
[2022-05-15 04:53:17.709] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] frame I:360   Avg QP:25.44  size:112431
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] frame P:22827 Avg QP:12.88  size: 69118
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] frame B:66812 Avg QP:18.43  size: 10093
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] consecutive B-frames:  0.8%  0.7%  0.2% 98.4%
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] mb I  I16..4: 48.5% 14.0% 37.6%
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] mb P  I16..4:  3.3%  1.8%  0.9%  P16..4: 27.6%  4.1%  3.9%  0.0%  0.0%    skip:58.5%
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] mb B  I16..4:  0.4%  0.4%  0.0%  B16..8:  4.6%  1.9%  0.4%  direct: 4.7%  skip:87.7%  L0:32.9% L1:49.0% BI:18.1%
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.720] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] 8x8 transform intra:31.1% inter:21.0%
[2022-05-15 04:53:17.720] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] coded y,uvDC,uvAC intra: 62.9% 69.5% 58.7% inter: 8.9% 5.9% 2.7%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] i16 v,h,dc,p: 48% 27% 13% 11%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 23% 33%  3%  3%  4%  4%  4%  5%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 31% 10%  4%  5%  5%  5%  4%  5%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] i8c dc,h,v,p: 45% 28% 20%  7%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1A6AD3B40] kb/s:10189.29
[2022-05-15 04:53:17.721] [info]    
[2022-05-15 04:53:17.881] [info]    ffmpeg[ch1/20220515042317.mp4] Uninitialized.
[2022-05-15 04:53:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515042347.mp4\r\n
[2022-05-15 04:53:47.562] [info]    ffmpeg[ch2/20220515042347.mp4] Uninitialized.
[2022-05-15 04:53:47.562] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 04:53:47.565] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515045347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 04:53:47.568] [info]    ffmpeg[ch2/20220515045347.mp4] Initialized.
[2022-05-15 04:53:47.568] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 04:53:47.577] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] using SAR=1/1
[2022-05-15 04:53:47.577] [info]    
[2022-05-15 04:53:47.577] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 04:53:47.577] [info]    
[2022-05-15 04:53:47.583] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 04:53:47.583] [info]    
[2022-05-15 04:53:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4D00] Pure channel mapping detected:
[2022-05-15 04:53:47.588] [info]    [ffmpeg]  0
[2022-05-15 04:53:47.588] [info]    [ffmpeg]  1
[2022-05-15 04:53:47.588] [info]    [ffmpeg] 
[2022-05-15 04:53:47.588] [info]    
[2022-05-15 04:53:47.596] [warning] ffmpeg[ch2/20220515045347.mp4] Unused option s=1920:1080
[2022-05-15 04:53:47.693] [info]    [ffmpeg] [aac @ 000002B137E044C0] Qavg: 415.916
[2022-05-15 04:53:47.693] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] frame I:374   Avg QP:23.22  size:104107
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] frame P:23320 Avg QP:17.95  size: 61391
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] frame B:66306 Avg QP:20.80  size: 10333
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] consecutive B-frames:  0.8%  2.6%  0.7% 95.9%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] mb I  I16..4: 26.3% 43.1% 30.6%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] mb P  I16..4:  9.1% 13.8%  3.0%  P16..4: 31.2% 12.5%  8.4%  0.0%  0.0%    skip:22.1%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] mb B  I16..4:  1.8%  1.5%  0.1%  B16..8: 14.1%  4.2%  0.4%  direct: 9.0%  skip:69.0%  L0:49.6% L1:37.5% BI:13.0%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] 8x8 transform intra:50.8% inter:30.0%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] coded y,uvDC,uvAC intra: 62.6% 61.1% 26.5% inter: 10.7% 12.4% 0.7%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] i16 v,h,dc,p: 35% 28% 26% 11%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 20% 30%  4%  5%  5%  5%  5%  5%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 24% 15%  5%  7%  7%  6%  5%  5%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] i8c dc,h,v,p: 46% 27% 22%  6%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] Weighted P-Frames: Y:0.8% UV:0.1%
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.700] [info]    [ffmpeg] [libx264 @ 000002B254A04540] kb/s:9580.80
[2022-05-15 04:53:47.700] [info]    
[2022-05-15 04:53:47.860] [info]    ffmpeg[ch2/20220515042347.mp4] Uninitialized.
[2022-05-15 05:23:17.609] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515045317.mp4\r\n
[2022-05-15 05:23:17.612] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 05:23:17.612] [info]    ffmpeg[ch1/20220515045317.mp4] Uninitialized.
[2022-05-15 05:23:17.614] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515052317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 05:23:17.614] [info]    ffmpeg[ch1/20220515052317.mp4] Initialized.
[2022-05-15 05:23:17.614] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 05:23:17.621] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] using SAR=1/1
[2022-05-15 05:23:17.621] [info]    
[2022-05-15 05:23:17.622] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 05:23:17.622] [info]    
[2022-05-15 05:23:17.628] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 05:23:17.628] [info]    
[2022-05-15 05:23:17.635] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1FF492E40] Pure channel mapping detected:
[2022-05-15 05:23:17.635] [info]    [ffmpeg]  0
[2022-05-15 05:23:17.635] [info]    [ffmpeg]  1
[2022-05-15 05:23:17.635] [info]    [ffmpeg] 
[2022-05-15 05:23:17.635] [info]    
[2022-05-15 05:23:17.644] [warning] ffmpeg[ch1/20220515052317.mp4] Unused option s=1920:1080
[2022-05-15 05:23:17.715] [info]    [ffmpeg] [aac @ 000002B194C993C0] Qavg: 18477.996
[2022-05-15 05:23:17.715] [info]    
[2022-05-15 05:23:17.727] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] frame I:361   Avg QP:26.36  size:111344
[2022-05-15 05:23:17.727] [info]    
[2022-05-15 05:23:17.727] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] frame P:22712 Avg QP:12.89  size: 69619
[2022-05-15 05:23:17.727] [info]    
[2022-05-15 05:23:17.727] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] frame B:66928 Avg QP:18.08  size: 10169
[2022-05-15 05:23:17.727] [info]    
[2022-05-15 05:23:17.727] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] consecutive B-frames:  0.8%  0.2%  0.1% 98.9%
[2022-05-15 05:23:17.727] [info]    
[2022-05-15 05:23:17.727] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] mb I  I16..4: 49.7% 12.6% 37.7%
[2022-05-15 05:23:17.727] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] mb P  I16..4:  3.6%  1.9%  0.9%  P16..4: 28.2%  3.4%  3.8%  0.0%  0.0%    skip:58.1%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] mb B  I16..4:  0.4%  0.4%  0.0%  B16..8:  4.4%  1.8%  0.4%  direct: 4.5%  skip:88.0%  L0:29.5% L1:54.2% BI:16.2%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] 8x8 transform intra:32.3% inter:21.7%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] coded y,uvDC,uvAC intra: 64.6% 70.7% 60.6% inter: 8.8% 6.0% 2.7%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] i16 v,h,dc,p: 47% 26% 16% 11%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 20% 36%  3%  3%  4%  4%  4%  5%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 11%  4%  6%  6%  5%  5%  5%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] i8c dc,h,v,p: 46% 29% 20%  6%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254FCBD00] kb/s:10230.97
[2022-05-15 05:23:17.728] [info]    
[2022-05-15 05:23:17.873] [info]    ffmpeg[ch1/20220515045317.mp4] Uninitialized.
[2022-05-15 05:23:47.561] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515045347.mp4\r\n
[2022-05-15 05:23:47.564] [info]    ffmpeg[ch2/20220515045347.mp4] Uninitialized.
[2022-05-15 05:23:47.564] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 05:23:47.569] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515052347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 05:23:47.570] [info]    ffmpeg[ch2/20220515052347.mp4] Initialized.
[2022-05-15 05:23:47.571] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 05:23:47.580] [info]    [ffmpeg] [libx264 @ 000002B25478A900] using SAR=1/1
[2022-05-15 05:23:47.580] [info]    
[2022-05-15 05:23:47.581] [info]    [ffmpeg] [libx264 @ 000002B25478A900] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 05:23:47.581] [info]    
[2022-05-15 05:23:47.586] [info]    [ffmpeg] [libx264 @ 000002B25478A900] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 05:23:47.586] [info]    
[2022-05-15 05:23:47.589] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1FF494440] Pure channel mapping detected:
[2022-05-15 05:23:47.589] [info]    [ffmpeg]  0
[2022-05-15 05:23:47.589] [info]    [ffmpeg]  1
[2022-05-15 05:23:47.590] [info]    [ffmpeg] 
[2022-05-15 05:23:47.590] [info]    
[2022-05-15 05:23:47.596] [warning] ffmpeg[ch2/20220515052347.mp4] Unused option s=1920:1080
[2022-05-15 05:23:47.699] [info]    [ffmpeg] [aac @ 000002B254B9EE40] Qavg: 280.379
[2022-05-15 05:23:47.699] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] frame I:361   Avg QP:24.13  size:105906
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] frame P:22983 Avg QP:17.80  size: 62238
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] frame B:66656 Avg QP:20.62  size: 10350
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] consecutive B-frames:  0.9%  1.0%  0.5% 97.7%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] mb I  I16..4: 28.5% 39.1% 32.4%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] mb P  I16..4:  8.4% 12.3%  2.9%  P16..4: 31.0% 11.9%  8.5%  0.0%  0.0%    skip:24.9%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] mb B  I16..4:  1.6%  1.3%  0.1%  B16..8: 14.1%  4.3%  0.4%  direct: 9.4%  skip:68.7%  L0:48.8% L1:37.5% BI:13.7%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] 8x8 transform intra:49.6% inter:29.6%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.703] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] coded y,uvDC,uvAC intra: 61.6% 62.1% 27.4% inter: 11.1% 12.7% 0.6%
[2022-05-15 05:23:47.703] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] i16 v,h,dc,p: 36% 27% 27% 10%
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 18% 33%  4%  4%  5%  4%  5%  4%
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 15%  5%  7%  7%  6%  5%  5%
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] i8c dc,h,v,p: 46% 27% 22%  5%
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.704] [info]    [ffmpeg] [libx264 @ 000002B1FED1EE40] kb/s:9593.36
[2022-05-15 05:23:47.704] [info]    
[2022-05-15 05:23:47.855] [info]    ffmpeg[ch2/20220515045347.mp4] Uninitialized.
[2022-05-15 05:53:17.607] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515052317.mp4\r\n
[2022-05-15 05:53:17.609] [info]    ffmpeg[ch1/20220515052317.mp4] Uninitialized.
[2022-05-15 05:53:17.613] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 05:53:17.617] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515055317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 05:53:17.618] [info]    ffmpeg[ch1/20220515055317.mp4] Initialized.
[2022-05-15 05:53:17.618] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 05:53:17.625] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] using SAR=1/1
[2022-05-15 05:53:17.625] [info]    
[2022-05-15 05:53:17.625] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 05:53:17.625] [info]    
[2022-05-15 05:53:17.631] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 05:53:17.631] [info]    
[2022-05-15 05:53:17.641] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1440] Pure channel mapping detected:
[2022-05-15 05:53:17.641] [info]    [ffmpeg]  0
[2022-05-15 05:53:17.641] [info]    [ffmpeg]  1
[2022-05-15 05:53:17.641] [info]    [ffmpeg] 
[2022-05-15 05:53:17.641] [info]    
[2022-05-15 05:53:17.652] [warning] ffmpeg[ch1/20220515055317.mp4] Unused option s=1920:1080
[2022-05-15 05:53:17.704] [info]    [ffmpeg] [aac @ 000002B254A04080] Qavg: 20715.498
[2022-05-15 05:53:17.704] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] frame I:360   Avg QP:28.71  size:114200
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] frame P:22823 Avg QP:16.16  size: 69535
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] frame B:66816 Avg QP:22.27  size:  9631
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] consecutive B-frames:  0.7%  0.8%  0.2% 98.3%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] mb I  I16..4: 41.5% 16.3% 42.2%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] mb P  I16..4:  3.1%  1.1%  1.6%  P16..4: 27.7%  6.0%  6.2%  0.0%  0.0%    skip:54.2%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] mb B  I16..4:  0.3%  0.1%  0.1%  B16..8:  4.9%  2.2%  0.6%  direct: 4.9%  skip:86.9%  L0:36.1% L1:42.0% BI:21.9%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] 8x8 transform intra:20.2% inter:22.2%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] coded y,uvDC,uvAC intra: 51.2% 58.5% 39.3% inter: 9.5% 6.6% 2.3%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] i16 v,h,dc,p: 55% 34%  4%  7%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 26% 17%  5%  6%  6%  6%  5%  6%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 29%  9%  4%  6%  6%  6%  4%  5%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] i8c dc,h,v,p: 42% 29% 25%  5%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.708] [info]    [ffmpeg] [libx264 @ 000002B1FF533A80] kb/s:10096.22
[2022-05-15 05:53:17.708] [info]    
[2022-05-15 05:53:17.862] [info]    ffmpeg[ch1/20220515052317.mp4] Uninitialized.
[2022-05-15 05:53:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515052347.mp4\r\n
[2022-05-15 05:53:47.560] [info]    ffmpeg[ch2/20220515052347.mp4] Uninitialized.
[2022-05-15 05:53:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 05:53:47.562] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515055347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 05:53:47.563] [info]    ffmpeg[ch2/20220515055347.mp4] Initialized.
[2022-05-15 05:53:47.563] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 05:53:47.581] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] using SAR=1/1
[2022-05-15 05:53:47.581] [info]    
[2022-05-15 05:53:47.581] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 05:53:47.581] [info]    
[2022-05-15 05:53:47.587] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 05:53:47.587] [info]    
[2022-05-15 05:53:47.594] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0440] Pure channel mapping detected:
[2022-05-15 05:53:47.594] [info]    [ffmpeg]  0
[2022-05-15 05:53:47.594] [info]    [ffmpeg]  1
[2022-05-15 05:53:47.594] [info]    [ffmpeg] 
[2022-05-15 05:53:47.594] [info]    
[2022-05-15 05:53:47.603] [warning] ffmpeg[ch2/20220515055347.mp4] Unused option s=1920:1080
[2022-05-15 05:53:47.653] [info]    [ffmpeg] [aac @ 000002B1FF73ADC0] Qavg: 541.906
[2022-05-15 05:53:47.653] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] frame I:372   Avg QP:23.60  size:104423
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] frame P:23269 Avg QP:18.65  size: 60000
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] frame B:66359 Avg QP:21.52  size: 10355
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] consecutive B-frames:  0.9%  2.1%  0.7% 96.3%
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] mb I  I16..4: 26.3% 42.8% 31.0%
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] mb P  I16..4:  9.6% 14.0%  2.6%  P16..4: 31.0% 12.5%  8.3%  0.0%  0.0%    skip:22.0%
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.662] [info]    [ffmpeg] [libx264 @ 000002B25478A900] mb B  I16..4:  1.8%  1.3%  0.1%  B16..8: 14.5%  4.3%  0.4%  direct: 9.7%  skip:68.0%  L0:46.4% L1:40.0% BI:13.6%
[2022-05-15 05:53:47.662] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] 8x8 transform intra:50.2% inter:29.1%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] coded y,uvDC,uvAC intra: 59.5% 56.2% 20.1% inter: 10.9% 12.0% 0.5%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] i16 v,h,dc,p: 33% 29% 26% 12%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 21% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 25% 14%  5%  7%  7%  6%  6%  5%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] i8c dc,h,v,p: 47% 26% 21%  5%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] Weighted P-Frames: Y:0.9% UV:0.1%
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.663] [info]    [ffmpeg] [libx264 @ 000002B25478A900] kb/s:9431.65
[2022-05-15 05:53:47.663] [info]    
[2022-05-15 05:53:47.822] [info]    ffmpeg[ch2/20220515052347.mp4] Uninitialized.
[2022-05-15 06:23:17.617] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515055317.mp4\r\n
[2022-05-15 06:23:17.619] [info]    ffmpeg[ch1/20220515055317.mp4] Uninitialized.
[2022-05-15 06:23:17.619] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 06:23:17.621] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515062317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 06:23:17.621] [info]    ffmpeg[ch1/20220515062317.mp4] Initialized.
[2022-05-15 06:23:17.621] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 06:23:17.628] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] using SAR=1/1
[2022-05-15 06:23:17.628] [info]    
[2022-05-15 06:23:17.628] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 06:23:17.628] [info]    
[2022-05-15 06:23:17.633] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 06:23:17.633] [info]    
[2022-05-15 06:23:17.641] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4B00] Pure channel mapping detected:
[2022-05-15 06:23:17.641] [info]    [ffmpeg]  0
[2022-05-15 06:23:17.641] [info]    [ffmpeg]  1
[2022-05-15 06:23:17.641] [info]    [ffmpeg] 
[2022-05-15 06:23:17.641] [info]    
[2022-05-15 06:23:17.649] [warning] ffmpeg[ch1/20220515062317.mp4] Unused option s=1920:1080
[2022-05-15 06:23:17.718] [info]    [ffmpeg] [aac @ 000002B1FF16A240] Qavg: 458.327
[2022-05-15 06:23:17.718] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] frame I:360   Avg QP:25.85  size:109099
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] frame P:22752 Avg QP:13.35  size: 65669
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] frame B:66888 Avg QP:19.37  size:  8382
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] consecutive B-frames:  0.8%  0.4%  0.2% 98.7%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] mb I  I16..4: 48.9% 12.7% 38.4%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] mb P  I16..4:  2.5%  0.4%  0.8%  P16..4: 27.5%  4.4%  4.8%  0.0%  0.0%    skip:59.6%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] mb B  I16..4:  0.1%  0.0%  0.0%  B16..8:  4.1%  1.8%  0.5%  direct: 4.6%  skip:88.8%  L0:37.1% L1:43.9% BI:19.0%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] 8x8 transform intra:12.2% inter:21.7%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] coded y,uvDC,uvAC intra: 42.7% 56.6% 45.8% inter: 8.7% 6.3% 2.9%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] i16 v,h,dc,p: 67% 28%  2%  2%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 28% 19%  4%  4%  4%  5%  4%  5%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 33% 31%  9%  4%  5%  5%  5%  4%  5%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] i8c dc,h,v,p: 45% 26% 25%  4%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.726] [info]    [ffmpeg] [libx264 @ 000002B254BFE3C0] kb/s:9306.85
[2022-05-15 06:23:17.726] [info]    
[2022-05-15 06:23:17.879] [info]    ffmpeg[ch1/20220515055317.mp4] Uninitialized.
[2022-05-15 06:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515055347.mp4\r\n
[2022-05-15 06:23:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 06:23:47.560] [info]    ffmpeg[ch2/20220515055347.mp4] Uninitialized.
[2022-05-15 06:23:47.562] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515062347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 06:23:47.564] [info]    ffmpeg[ch2/20220515062347.mp4] Initialized.
[2022-05-15 06:23:47.564] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 06:23:47.583] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] using SAR=1/1
[2022-05-15 06:23:47.583] [info]    
[2022-05-15 06:23:47.583] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 06:23:47.583] [info]    
[2022-05-15 06:23:47.589] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 06:23:47.589] [info]    
[2022-05-15 06:23:47.596] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4D00] Pure channel mapping detected:
[2022-05-15 06:23:47.596] [info]    [ffmpeg]  0
[2022-05-15 06:23:47.596] [info]    [ffmpeg]  1
[2022-05-15 06:23:47.596] [info]    [ffmpeg] 
[2022-05-15 06:23:47.596] [info]    
[2022-05-15 06:23:47.602] [warning] ffmpeg[ch2/20220515062347.mp4] Unused option s=1920:1080
[2022-05-15 06:23:47.717] [info]    [ffmpeg] [aac @ 000002B194B42080] Qavg: 391.627
[2022-05-15 06:23:47.717] [info]    
[2022-05-15 06:23:47.723] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] frame I:396   Avg QP:24.43  size:105650
[2022-05-15 06:23:47.723] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] frame P:23573 Avg QP:18.49  size: 62144
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] frame B:66031 Avg QP:21.84  size: 10077
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] consecutive B-frames:  1.4%  2.1%  0.8% 95.7%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] mb I  I16..4: 21.9% 47.4% 30.7%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] mb P  I16..4:  8.0% 10.9%  2.6%  P16..4: 35.6% 14.2%  9.2%  0.0%  0.0%    skip:19.5%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] mb B  I16..4:  1.1%  1.1%  0.1%  B16..8: 14.7%  4.3%  0.4%  direct:10.4%  skip:67.9%  L0:44.5% L1:41.1% BI:14.3%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] 8x8 transform intra:50.2% inter:32.2%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] coded y,uvDC,uvAC intra: 53.6% 60.4% 25.0% inter: 12.0% 15.5% 1.0%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] i16 v,h,dc,p: 45% 28% 18%  9%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 22% 22%  4%  5%  6%  5%  5%  5%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 24% 13%  5%  7%  7%  6%  5%  5%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] i8c dc,h,v,p: 46% 25% 23%  7%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] Weighted P-Frames: Y:0.9% UV:0.3%
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.724] [info]    [ffmpeg] [libx264 @ 000002B1FF4EF340] kb/s:9654.08
[2022-05-15 06:23:47.724] [info]    
[2022-05-15 06:23:47.879] [info]    ffmpeg[ch2/20220515055347.mp4] Uninitialized.
[2022-05-15 06:53:17.611] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515062317.mp4\r\n
[2022-05-15 06:53:17.613] [info]    ffmpeg[ch1/20220515062317.mp4] Uninitialized.
[2022-05-15 06:53:17.613] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 06:53:17.617] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515065317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 06:53:17.618] [info]    ffmpeg[ch1/20220515065317.mp4] Initialized.
[2022-05-15 06:53:17.618] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 06:53:17.627] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] using SAR=1/1
[2022-05-15 06:53:17.627] [info]    
[2022-05-15 06:53:17.627] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 06:53:17.627] [info]    
[2022-05-15 06:53:17.633] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 06:53:17.633] [info]    
[2022-05-15 06:53:17.638] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1140] Pure channel mapping detected:
[2022-05-15 06:53:17.638] [info]    [ffmpeg]  0
[2022-05-15 06:53:17.638] [info]    [ffmpeg]  1
[2022-05-15 06:53:17.639] [info]    [ffmpeg] 
[2022-05-15 06:53:17.639] [info]    
[2022-05-15 06:53:17.643] [warning] ffmpeg[ch1/20220515065317.mp4] Unused option s=1920:1080
[2022-05-15 06:53:17.720] [info]    [ffmpeg] [aac @ 000002B1956062C0] Qavg: 8899.365
[2022-05-15 06:53:17.720] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] frame I:360   Avg QP:27.16  size:114597
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] frame P:22819 Avg QP:15.45  size: 67476
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] frame B:66821 Avg QP:21.67  size:  9943
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] consecutive B-frames:  0.7%  0.7%  0.2% 98.3%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] mb I  I16..4: 43.3% 16.4% 40.3%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] mb P  I16..4:  3.1%  1.2%  1.7%  P16..4: 26.2%  6.1%  6.1%  0.0%  0.0%    skip:55.6%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] mb B  I16..4:  0.3%  0.2%  0.1%  B16..8:  5.3%  2.3%  0.6%  direct: 4.8%  skip:86.4%  L0:38.4% L1:41.0% BI:20.7%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] 8x8 transform intra:21.8% inter:22.0%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] coded y,uvDC,uvAC intra: 53.3% 61.3% 42.6% inter: 9.1% 6.8% 2.3%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] i16 v,h,dc,p: 57% 32%  4%  7%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 26% 17%  5%  6%  6%  6%  5%  6%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] i8c dc,h,v,p: 40% 28% 26%  6%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.725] [info]    [ffmpeg] [libx264 @ 000002B194DF2000] kb/s:9979.41
[2022-05-15 06:53:17.725] [info]    
[2022-05-15 06:53:17.872] [info]    ffmpeg[ch1/20220515062317.mp4] Uninitialized.
[2022-05-15 06:53:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515062347.mp4\r\n
[2022-05-15 06:53:47.559] [info]    ffmpeg[ch2/20220515062347.mp4] Uninitialized.
[2022-05-15 06:53:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 06:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515065347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 06:53:47.561] [info]    ffmpeg[ch2/20220515065347.mp4] Initialized.
[2022-05-15 06:53:47.561] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 06:53:47.571] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] using SAR=1/1
[2022-05-15 06:53:47.571] [info]    
[2022-05-15 06:53:47.571] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 06:53:47.571] [info]    
[2022-05-15 06:53:47.582] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 06:53:47.582] [info]    
[2022-05-15 06:53:47.589] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1A40] Pure channel mapping detected:
[2022-05-15 06:53:47.589] [info]    [ffmpeg]  0
[2022-05-15 06:53:47.589] [info]    [ffmpeg]  1
[2022-05-15 06:53:47.589] [info]    [ffmpeg] 
[2022-05-15 06:53:47.589] [info]    
[2022-05-15 06:53:47.596] [warning] ffmpeg[ch2/20220515065347.mp4] Unused option s=1920:1080
[2022-05-15 06:53:47.687] [info]    [ffmpeg] [aac @ 000002B15E8069C0] Qavg: 525.594
[2022-05-15 06:53:47.687] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] frame I:380   Avg QP:23.96  size:105783
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] frame P:23387 Avg QP:18.50  size: 60823
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] frame B:66233 Avg QP:21.79  size: 10793
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] consecutive B-frames:  1.0%  2.5%  0.8% 95.8%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] mb I  I16..4: 27.8% 40.4% 31.8%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] mb P  I16..4:  9.3% 12.5%  2.8%  P16..4: 30.4% 12.0%  8.2%  0.0%  0.0%    skip:24.8%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] mb B  I16..4:  1.5%  1.3%  0.1%  B16..8: 13.9%  4.4%  0.5%  direct: 9.3%  skip:68.9%  L0:45.9% L1:39.8% BI:14.3%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] 8x8 transform intra:49.0% inter:28.1%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] coded y,uvDC,uvAC intra: 56.0% 58.0% 22.3% inter: 11.1% 11.9% 0.8%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] i16 v,h,dc,p: 38% 29% 23% 10%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 21% 26%  4%  5%  6%  5%  5%  5%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 24% 13%  5%  7%  7%  6%  6%  5%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] i8c dc,h,v,p: 47% 26% 21%  6%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] Weighted P-Frames: Y:0.8% UV:0.3%
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.701] [info]    [ffmpeg] [libx264 @ 000002B1A65CBA40] kb/s:9677.92
[2022-05-15 06:53:47.701] [info]    
[2022-05-15 06:53:47.864] [info]    ffmpeg[ch2/20220515062347.mp4] Uninitialized.
[2022-05-15 07:23:17.613] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515065317.mp4\r\n
[2022-05-15 07:23:17.615] [info]    ffmpeg[ch1/20220515065317.mp4] Uninitialized.
[2022-05-15 07:23:17.615] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 07:23:17.620] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515072317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 07:23:17.621] [info]    ffmpeg[ch1/20220515072317.mp4] Initialized.
[2022-05-15 07:23:17.621] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 07:23:17.631] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] using SAR=1/1
[2022-05-15 07:23:17.631] [info]    
[2022-05-15 07:23:17.631] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 07:23:17.631] [info]    
[2022-05-15 07:23:17.639] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 07:23:17.639] [info]    
[2022-05-15 07:23:17.649] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4900] Pure channel mapping detected:
[2022-05-15 07:23:17.650] [info]    [ffmpeg]  0
[2022-05-15 07:23:17.650] [info]    [ffmpeg]  1
[2022-05-15 07:23:17.650] [info]    [ffmpeg] 
[2022-05-15 07:23:17.650] [info]    
[2022-05-15 07:23:17.664] [warning] ffmpeg[ch1/20220515072317.mp4] Unused option s=1920:1080
[2022-05-15 07:23:17.720] [info]    [ffmpeg] [aac @ 000002B1FF250EC0] Qavg: 7284.929
[2022-05-15 07:23:17.720] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] frame I:360   Avg QP:24.19  size:111848
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] frame P:22719 Avg QP:13.64  size: 66278
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] frame B:66921 Avg QP:19.09  size:  8595
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] consecutive B-frames:  0.8%  0.2%  0.1% 98.9%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] mb I  I16..4: 48.4% 13.7% 37.9%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] mb P  I16..4:  2.7%  0.8%  1.0%  P16..4: 26.9%  5.4%  5.2%  0.0%  0.0%    skip:57.9%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  5.3%  2.1%  0.5%  direct: 4.9%  skip:87.0%  L0:42.8% L1:38.0% BI:19.2%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] 8x8 transform intra:16.8% inter:22.0%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] coded y,uvDC,uvAC intra: 50.0% 59.9% 48.2% inter: 9.2% 5.8% 2.3%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] i16 v,h,dc,p: 62% 29%  3%  6%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 29% 19%  4%  5%  5%  6%  5%  5%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 32% 30% 10%  4%  5%  5%  6%  4%  5%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] i8c dc,h,v,p: 44% 28% 24%  4%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.725] [info]    [ffmpeg] [libx264 @ 000002B1A69280C0] kb/s:9427.54
[2022-05-15 07:23:17.725] [info]    
[2022-05-15 07:23:17.882] [info]    ffmpeg[ch1/20220515065317.mp4] Uninitialized.
[2022-05-15 07:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515065347.mp4\r\n
[2022-05-15 07:23:47.559] [info]    ffmpeg[ch2/20220515065347.mp4] Uninitialized.
[2022-05-15 07:23:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 07:23:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515072347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 07:23:47.561] [info]    ffmpeg[ch2/20220515072347.mp4] Initialized.
[2022-05-15 07:23:47.561] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 07:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] using SAR=1/1
[2022-05-15 07:23:47.568] [info]    
[2022-05-15 07:23:47.569] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 07:23:47.569] [info]    
[2022-05-15 07:23:47.580] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 07:23:47.580] [info]    
[2022-05-15 07:23:47.590] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5100] Pure channel mapping detected:
[2022-05-15 07:23:47.590] [info]    [ffmpeg]  0
[2022-05-15 07:23:47.590] [info]    [ffmpeg]  1
[2022-05-15 07:23:47.590] [info]    [ffmpeg] 
[2022-05-15 07:23:47.590] [info]    
[2022-05-15 07:23:47.593] [warning] ffmpeg[ch2/20220515072347.mp4] Unused option s=1920:1080
[2022-05-15 07:23:47.679] [info]    [ffmpeg] [aac @ 000002B1FF127C40] Qavg: 244.521
[2022-05-15 07:23:47.679] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] frame I:360   Avg QP:23.50  size:110830
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] frame P:22764 Avg QP:15.65  size: 64522
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] frame B:66876 Avg QP:18.22  size: 11113
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] consecutive B-frames:  0.8%  0.3%  0.2% 98.6%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] mb I  I16..4: 34.1% 32.3% 33.6%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] mb P  I16..4:  6.5%  5.5%  1.6%  P16..4: 37.5% 13.4% 10.3%  0.0%  0.0%    skip:25.2%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] mb B  I16..4:  0.8%  0.5%  0.1%  B16..8: 14.4%  4.7%  0.5%  direct:10.4%  skip:68.7%  L0:48.6% L1:36.9% BI:14.5%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] 8x8 transform intra:39.2% inter:26.6%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] coded y,uvDC,uvAC intra: 63.4% 75.4% 53.1% inter: 12.5% 12.8% 1.1%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] i16 v,h,dc,p: 46% 25% 23%  6%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 16% 32%  4%  5%  6%  5%  6%  5%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 21% 18%  5%  6%  6%  6%  6%  5%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] i8c dc,h,v,p: 45% 27% 23%  6%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.683] [info]    [ffmpeg] [libx264 @ 000002B1FF436980] kb/s:10008.43
[2022-05-15 07:23:47.683] [info]    
[2022-05-15 07:23:47.833] [info]    ffmpeg[ch2/20220515065347.mp4] Uninitialized.
[2022-05-15 07:53:17.623] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515072317.mp4\r\n
[2022-05-15 07:53:17.624] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 07:53:17.625] [info]    ffmpeg[ch1/20220515072317.mp4] Uninitialized.
[2022-05-15 07:53:17.627] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515075317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 07:53:17.628] [info]    ffmpeg[ch1/20220515075317.mp4] Initialized.
[2022-05-15 07:53:17.628] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 07:53:17.635] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] using SAR=1/1
[2022-05-15 07:53:17.635] [info]    
[2022-05-15 07:53:17.636] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 07:53:17.636] [info]    
[2022-05-15 07:53:17.641] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 07:53:17.641] [info]    
[2022-05-15 07:53:17.648] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0840] Pure channel mapping detected:
[2022-05-15 07:53:17.648] [info]    [ffmpeg]  0
[2022-05-15 07:53:17.648] [info]    [ffmpeg]  1
[2022-05-15 07:53:17.648] [info]    [ffmpeg] 
[2022-05-15 07:53:17.648] [info]    
[2022-05-15 07:53:17.657] [warning] ffmpeg[ch1/20220515075317.mp4] Unused option s=1920:1080
[2022-05-15 07:53:17.717] [info]    [ffmpeg] [aac @ 000002B25488F340] Qavg: 20730.189
[2022-05-15 07:53:17.717] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] frame I:360   Avg QP:28.25  size:113929
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] frame P:22771 Avg QP:15.44  size: 68867
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] frame B:66869 Avg QP:21.56  size:  9494
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] consecutive B-frames:  0.7%  0.5%  0.2% 98.6%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] mb I  I16..4: 42.3% 16.5% 41.2%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] mb P  I16..4:  2.9%  0.8%  1.4%  P16..4: 27.9%  5.3%  5.7%  0.0%  0.0%    skip:56.0%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  5.0%  2.1%  0.6%  direct: 4.9%  skip:87.1%  L0:37.5% L1:41.9% BI:20.6%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] 8x8 transform intra:17.3% inter:21.8%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.721] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] coded y,uvDC,uvAC intra: 50.2% 57.0% 40.5% inter: 9.3% 6.5% 2.3%
[2022-05-15 07:53:17.721] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] i16 v,h,dc,p: 61% 32%  3%  5%
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 27% 16%  4%  5%  5%  6%  5%  5%
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28%  9%  4%  6%  6%  6%  5%  5%
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] i8c dc,h,v,p: 42% 28% 26%  4%
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.722] [info]    [ffmpeg] [libx264 @ 000002B1FF251C80] kb/s:9973.65
[2022-05-15 07:53:17.722] [info]    
[2022-05-15 07:53:17.876] [info]    ffmpeg[ch1/20220515072317.mp4] Uninitialized.
[2022-05-15 07:53:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515072347.mp4\r\n
[2022-05-15 07:53:47.559] [info]    ffmpeg[ch2/20220515072347.mp4] Uninitialized.
[2022-05-15 07:53:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 07:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515075347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 07:53:47.561] [info]    ffmpeg[ch2/20220515075347.mp4] Initialized.
[2022-05-15 07:53:47.561] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 07:53:47.566] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] using SAR=1/1
[2022-05-15 07:53:47.566] [info]    
[2022-05-15 07:53:47.567] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 07:53:47.567] [info]    
[2022-05-15 07:53:47.575] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 07:53:47.575] [info]    
[2022-05-15 07:53:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1840] Pure channel mapping detected:
[2022-05-15 07:53:47.588] [info]    [ffmpeg]  0
[2022-05-15 07:53:47.588] [info]    [ffmpeg]  1
[2022-05-15 07:53:47.588] [info]    [ffmpeg] 
[2022-05-15 07:53:47.588] [info]    
[2022-05-15 07:53:47.591] [warning] ffmpeg[ch2/20220515075347.mp4] Unused option s=1920:1080
[2022-05-15 07:53:47.651] [info]    [ffmpeg] [aac @ 000002B1951E0DC0] Qavg: 460.307
[2022-05-15 07:53:47.651] [info]    
[2022-05-15 07:53:47.664] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] frame I:383   Avg QP:23.94  size:106804
[2022-05-15 07:53:47.664] [info]    
[2022-05-15 07:53:47.664] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] frame P:23756 Avg QP:18.01  size: 60475
[2022-05-15 07:53:47.664] [info]    
[2022-05-15 07:53:47.664] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] frame B:65861 Avg QP:21.16  size: 10269
[2022-05-15 07:53:47.664] [info]    
[2022-05-15 07:53:47.664] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] consecutive B-frames:  1.0%  3.8%  1.7% 93.5%
[2022-05-15 07:53:47.664] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] mb I  I16..4: 26.5% 40.7% 32.8%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] mb P  I16..4:  8.0% 11.8%  2.4%  P16..4: 32.4% 11.4%  8.0%  0.0%  0.0%    skip:26.1%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] mb B  I16..4:  1.6%  1.3%  0.1%  B16..8: 13.3%  4.0%  0.4%  direct: 9.4%  skip:69.9%  L0:45.7% L1:39.9% BI:14.4%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] 8x8 transform intra:50.3% inter:28.1%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] coded y,uvDC,uvAC intra: 60.6% 55.5% 21.7% inter: 11.1% 11.5% 0.6%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] i16 v,h,dc,p: 35% 27% 26% 12%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 18% 30%  4%  5%  6%  5%  5%  5%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 23% 14%  5%  7%  7%  6%  6%  5%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] i8c dc,h,v,p: 48% 25% 22%  5%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] Weighted P-Frames: Y:0.3% UV:0.0%
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B1953F1040] kb/s:9572.83
[2022-05-15 07:53:47.665] [info]    
[2022-05-15 07:53:47.826] [info]    ffmpeg[ch2/20220515072347.mp4] Uninitialized.
[2022-05-15 08:23:17.626] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515075317.mp4\r\n
[2022-05-15 08:23:17.627] [info]    ffmpeg[ch1/20220515075317.mp4] Uninitialized.
[2022-05-15 08:23:17.627] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 08:23:17.629] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515082317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 08:23:17.630] [info]    ffmpeg[ch1/20220515082317.mp4] Initialized.
[2022-05-15 08:23:17.630] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 08:23:17.639] [info]    [ffmpeg] [libx264 @ 000002B15E929400] using SAR=1/1
[2022-05-15 08:23:17.639] [info]    
[2022-05-15 08:23:17.640] [info]    [ffmpeg] [libx264 @ 000002B15E929400] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 08:23:17.640] [info]    
[2022-05-15 08:23:17.647] [info]    [ffmpeg] [libx264 @ 000002B15E929400] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 08:23:17.647] [info]    
[2022-05-15 08:23:17.660] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4800] Pure channel mapping detected:
[2022-05-15 08:23:17.660] [info]    [ffmpeg]  0
[2022-05-15 08:23:17.660] [info]    [ffmpeg]  1
[2022-05-15 08:23:17.660] [info]    [ffmpeg] 
[2022-05-15 08:23:17.660] [info]    
[2022-05-15 08:23:17.669] [warning] ffmpeg[ch1/20220515082317.mp4] Unused option s=1920:1080
[2022-05-15 08:23:17.724] [info]    [ffmpeg] [aac @ 000002B194B41C00] Qavg: 12472.620
[2022-05-15 08:23:17.724] [info]    
[2022-05-15 08:23:17.728] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] frame I:360   Avg QP:25.94  size:110448
[2022-05-15 08:23:17.728] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] frame P:22800 Avg QP:14.75  size: 65444
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] frame B:66840 Avg QP:21.17  size:  9421
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] consecutive B-frames:  0.8%  0.6%  0.2% 98.4%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] mb I  I16..4: 48.2% 14.4% 37.4%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] mb P  I16..4:  2.6%  0.8%  1.4%  P16..4: 24.1%  5.5%  5.8%  0.0%  0.0%    skip:60.0%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  5.2%  2.3%  0.6%  direct: 4.6%  skip:87.0%  L0:40.2% L1:38.9% BI:20.9%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] 8x8 transform intra:17.9% inter:20.7%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] coded y,uvDC,uvAC intra: 51.8% 61.6% 47.1% inter: 8.8% 6.5% 2.7%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] i16 v,h,dc,p: 58% 33%  5%  5%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 28% 18%  4%  5%  5%  5%  5%  6%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 29% 30% 10%  4%  5%  6%  6%  5%  5%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] i8c dc,h,v,p: 39% 30% 25%  5%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.729] [info]    [ffmpeg] [libx264 @ 000002B254C50FC0] kb/s:9606.96
[2022-05-15 08:23:17.729] [info]    
[2022-05-15 08:23:17.878] [info]    ffmpeg[ch1/20220515075317.mp4] Uninitialized.
[2022-05-15 08:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515075347.mp4\r\n
[2022-05-15 08:23:47.560] [info]    ffmpeg[ch2/20220515075347.mp4] Uninitialized.
[2022-05-15 08:23:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 08:23:47.562] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515082347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 08:23:47.562] [info]    ffmpeg[ch2/20220515082347.mp4] Initialized.
[2022-05-15 08:23:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 08:23:47.567] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] using SAR=1/1
[2022-05-15 08:23:47.567] [info]    
[2022-05-15 08:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 08:23:47.568] [info]    
[2022-05-15 08:23:47.575] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 08:23:47.575] [info]    
[2022-05-15 08:23:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4E00] Pure channel mapping detected:
[2022-05-15 08:23:47.588] [info]    [ffmpeg]  0
[2022-05-15 08:23:47.588] [info]    [ffmpeg]  1
[2022-05-15 08:23:47.588] [info]    [ffmpeg] 
[2022-05-15 08:23:47.588] [info]    
[2022-05-15 08:23:47.592] [warning] ffmpeg[ch2/20220515082347.mp4] Unused option s=1920:1080
[2022-05-15 08:23:47.670] [info]    [ffmpeg] [aac @ 000002B254D18E80] Qavg: 521.631
[2022-05-15 08:23:47.670] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] frame I:374   Avg QP:24.53  size:106020
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] frame P:23456 Avg QP:19.05  size: 60622
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] frame B:66170 Avg QP:21.91  size: 10212
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] consecutive B-frames:  1.0%  2.3%  1.9% 94.8%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] mb I  I16..4: 24.6% 42.4% 32.9%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] mb P  I16..4:  9.0% 13.7%  2.6%  P16..4: 32.5% 12.2%  8.1%  0.0%  0.0%    skip:22.0%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] mb B  I16..4:  1.7%  1.5%  0.1%  B16..8: 13.8%  4.2%  0.4%  direct: 9.6%  skip:68.8%  L0:44.8% L1:41.4% BI:13.9%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] 8x8 transform intra:51.3% inter:31.2%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] coded y,uvDC,uvAC intra: 58.2% 57.7% 21.4% inter: 11.2% 12.5% 0.5%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] i16 v,h,dc,p: 35% 29% 25% 11%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 20% 29%  4%  5%  6%  5%  5%  4%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 24% 14%  5%  7%  7%  6%  6%  5%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] i8c dc,h,v,p: 46% 27% 22%  5%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] Weighted P-Frames: Y:0.6% UV:0.2%
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.676] [info]    [ffmpeg] [libx264 @ 000002B1FF4EEEC0] kb/s:9499.32
[2022-05-15 08:23:47.676] [info]    
[2022-05-15 08:23:47.835] [info]    ffmpeg[ch2/20220515075347.mp4] Uninitialized.
[2022-05-15 08:53:17.626] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515082317.mp4\r\n
[2022-05-15 08:53:17.627] [info]    ffmpeg[ch1/20220515082317.mp4] Uninitialized.
[2022-05-15 08:53:17.627] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 08:53:17.629] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515085317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 08:53:17.630] [info]    ffmpeg[ch1/20220515085317.mp4] Initialized.
[2022-05-15 08:53:17.630] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 08:53:17.639] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] using SAR=1/1
[2022-05-15 08:53:17.639] [info]    
[2022-05-15 08:53:17.640] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 08:53:17.640] [info]    
[2022-05-15 08:53:17.648] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 08:53:17.648] [info]    
[2022-05-15 08:53:17.659] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0840] Pure channel mapping detected:
[2022-05-15 08:53:17.659] [info]    [ffmpeg]  0
[2022-05-15 08:53:17.659] [info]    [ffmpeg]  1
[2022-05-15 08:53:17.659] [info]    [ffmpeg] 
[2022-05-15 08:53:17.659] [info]    
[2022-05-15 08:53:17.667] [warning] ffmpeg[ch1/20220515085317.mp4] Unused option s=1920:1080
[2022-05-15 08:53:17.724] [info]    [ffmpeg] [aac @ 000002B254D19300] Qavg: 6870.436
[2022-05-15 08:53:17.724] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] frame I:360   Avg QP:29.63  size:114487
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] frame P:22792 Avg QP:16.22  size: 69168
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] frame B:66848 Avg QP:22.30  size:  9910
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] consecutive B-frames:  0.8%  0.6%  0.2% 98.5%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] mb I  I16..4: 38.5% 19.3% 42.2%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] mb P  I16..4:  2.4%  1.0%  1.4%  P16..4: 28.2%  6.4%  6.4%  0.0%  0.0%    skip:54.2%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  5.1%  2.3%  0.6%  direct: 4.9%  skip:86.7%  L0:35.9% L1:42.1% BI:22.0%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] 8x8 transform intra:22.1% inter:21.6%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] coded y,uvDC,uvAC intra: 56.1% 60.0% 41.0% inter: 9.5% 7.0% 2.4%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] i16 v,h,dc,p: 49% 39%  5%  7%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 25% 19%  5%  5%  6%  5%  5%  6%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 29% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.728] [info]    [ffmpeg] [libx264 @ 000002B15E929400] i8c dc,h,v,p: 36% 31% 27%  6%
[2022-05-15 08:53:17.728] [info]    
[2022-05-15 08:53:17.729] [info]    [ffmpeg] [libx264 @ 000002B15E929400] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 08:53:17.729] [info]    
[2022-05-15 08:53:17.729] [info]    [ffmpeg] [libx264 @ 000002B15E929400] kb/s:10133.98
[2022-05-15 08:53:17.729] [info]    
[2022-05-15 08:53:17.881] [info]    ffmpeg[ch1/20220515082317.mp4] Uninitialized.
[2022-05-15 08:53:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515082347.mp4\r\n
[2022-05-15 08:53:47.559] [info]    ffmpeg[ch2/20220515082347.mp4] Uninitialized.
[2022-05-15 08:53:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 08:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515085347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 08:53:47.562] [info]    ffmpeg[ch2/20220515085347.mp4] Initialized.
[2022-05-15 08:53:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 08:53:47.567] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] using SAR=1/1
[2022-05-15 08:53:47.567] [info]    
[2022-05-15 08:53:47.567] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 08:53:47.567] [info]    
[2022-05-15 08:53:47.573] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 08:53:47.573] [info]    
[2022-05-15 08:53:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0440] Pure channel mapping detected:
[2022-05-15 08:53:47.588] [info]    [ffmpeg]  0
[2022-05-15 08:53:47.588] [info]    [ffmpeg]  1
[2022-05-15 08:53:47.588] [info]    [ffmpeg] 
[2022-05-15 08:53:47.588] [info]    
[2022-05-15 08:53:47.594] [warning] ffmpeg[ch2/20220515085347.mp4] Unused option s=1920:1080
[2022-05-15 08:53:47.713] [info]    [ffmpeg] [aac @ 000002B137AE5500] Qavg: 528.914
[2022-05-15 08:53:47.713] [info]    
[2022-05-15 08:53:47.719] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] frame I:379   Avg QP:24.27  size:102575
[2022-05-15 08:53:47.719] [info]    
[2022-05-15 08:53:47.719] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] frame P:24015 Avg QP:20.31  size: 58246
[2022-05-15 08:53:47.719] [info]    
[2022-05-15 08:53:47.719] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] frame B:65606 Avg QP:23.40  size: 10441
[2022-05-15 08:53:47.719] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] consecutive B-frames:  1.2%  4.4%  1.2% 93.2%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] mb I  I16..4: 24.7% 45.7% 29.6%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] mb P  I16..4: 11.0% 17.2%  2.9%  P16..4: 28.9% 12.6%  7.6%  0.0%  0.0%    skip:19.8%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] mb B  I16..4:  2.0%  1.8%  0.1%  B16..8: 15.0%  4.4%  0.4%  direct: 9.3%  skip:67.2%  L0:42.7% L1:44.5% BI:12.9%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] 8x8 transform intra:52.8% inter:30.6%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] coded y,uvDC,uvAC intra: 52.9% 54.5% 16.4% inter: 10.8% 11.8% 0.4%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] i16 v,h,dc,p: 33% 33% 23% 11%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 27% 24%  4%  5%  5%  5%  5%  5%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 27% 13%  5%  6%  6%  6%  5%  5%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] i8c dc,h,v,p: 45% 28% 21%  6%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] Weighted P-Frames: Y:1.2% UV:0.3%
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.720] [info]    [ffmpeg] [libx264 @ 000002B1FF84C240] kb/s:9433.86
[2022-05-15 08:53:47.720] [info]    
[2022-05-15 08:53:47.880] [info]    ffmpeg[ch2/20220515082347.mp4] Uninitialized.
[2022-05-15 09:23:17.628] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515085317.mp4\r\n
[2022-05-15 09:23:17.629] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 09:23:17.629] [info]    ffmpeg[ch1/20220515085317.mp4] Uninitialized.
[2022-05-15 09:23:17.636] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515092317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 09:23:17.637] [info]    ffmpeg[ch1/20220515092317.mp4] Initialized.
[2022-05-15 09:23:17.638] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 09:23:17.645] [info]    [ffmpeg] [libx264 @ 000002B195660740] using SAR=1/1
[2022-05-15 09:23:17.645] [info]    
[2022-05-15 09:23:17.645] [info]    [ffmpeg] [libx264 @ 000002B195660740] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 09:23:17.645] [info]    
[2022-05-15 09:23:17.652] [info]    [ffmpeg] [libx264 @ 000002B195660740] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 09:23:17.652] [info]    
[2022-05-15 09:23:17.662] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5100] Pure channel mapping detected:
[2022-05-15 09:23:17.662] [info]    [ffmpeg]  0
[2022-05-15 09:23:17.663] [info]    [ffmpeg]  1
[2022-05-15 09:23:17.663] [info]    [ffmpeg] 
[2022-05-15 09:23:17.663] [info]    
[2022-05-15 09:23:17.684] [warning] ffmpeg[ch1/20220515092317.mp4] Unused option s=1920:1080
[2022-05-15 09:23:17.712] [info]    [ffmpeg] [aac @ 000002B194E7B500] Qavg: 8153.229
[2022-05-15 09:23:17.712] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] frame I:360   Avg QP:27.77  size:112612
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] frame P:22818 Avg QP:15.05  size: 67464
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] frame B:66821 Avg QP:21.49  size:  8796
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] consecutive B-frames:  0.8%  0.7%  0.1% 98.4%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] mb I  I16..4: 42.8% 17.5% 39.7%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] mb P  I16..4:  1.9%  0.6%  1.2%  P16..4: 27.2%  5.5%  6.0%  0.0%  0.0%    skip:57.7%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.8%  2.1%  0.6%  direct: 4.5%  skip:87.8%  L0:39.1% L1:39.9% BI:21.0%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] 8x8 transform intra:17.4% inter:20.8%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] coded y,uvDC,uvAC intra: 54.0% 58.2% 43.3% inter: 9.0% 6.6% 2.6%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] i16 v,h,dc,p: 53% 40%  3%  5%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 29% 16%  4%  5%  5%  6%  5%  6%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 31% 10%  4%  5%  5%  6%  5%  5%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] i8c dc,h,v,p: 35% 33% 26%  5%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.722] [info]    [ffmpeg] [libx264 @ 000002B19542EA40] kb/s:9634.16
[2022-05-15 09:23:17.722] [info]    
[2022-05-15 09:23:17.874] [info]    ffmpeg[ch1/20220515085317.mp4] Uninitialized.
[2022-05-15 09:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515085347.mp4\r\n
[2022-05-15 09:23:47.560] [info]    ffmpeg[ch2/20220515085347.mp4] Uninitialized.
[2022-05-15 09:23:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 09:23:47.562] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515092347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 09:23:47.563] [info]    ffmpeg[ch2/20220515092347.mp4] Initialized.
[2022-05-15 09:23:47.563] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 09:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] using SAR=1/1
[2022-05-15 09:23:47.568] [info]    
[2022-05-15 09:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 09:23:47.568] [info]    
[2022-05-15 09:23:47.573] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 09:23:47.573] [info]    
[2022-05-15 09:23:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5900] Pure channel mapping detected:
[2022-05-15 09:23:47.589] [info]    [ffmpeg]  0
[2022-05-15 09:23:47.589] [info]    [ffmpeg]  1
[2022-05-15 09:23:47.589] [info]    [ffmpeg] 
[2022-05-15 09:23:47.589] [info]    
[2022-05-15 09:23:47.597] [warning] ffmpeg[ch2/20220515092347.mp4] Unused option s=1920:1080
[2022-05-15 09:23:47.706] [info]    [ffmpeg] [aac @ 000002B1A6653B40] Qavg: 514.728
[2022-05-15 09:23:47.706] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] frame I:399   Avg QP:24.42  size:101477
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] frame P:23745 Avg QP:20.67  size: 58580
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] frame B:65856 Avg QP:23.65  size: 10561
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] consecutive B-frames:  1.1%  3.5%  1.2% 94.2%
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] mb I  I16..4: 25.8% 45.7% 28.5%
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] mb P  I16..4: 11.9% 17.9%  2.9%  P16..4: 29.6% 12.3%  7.4%  0.0%  0.0%    skip:18.1%
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.712] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] mb B  I16..4:  2.0%  1.9%  0.1%  B16..8: 15.2%  4.4%  0.4%  direct: 9.8%  skip:66.3%  L0:47.6% L1:40.0% BI:12.5%
[2022-05-15 09:23:47.712] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] 8x8 transform intra:52.6% inter:32.0%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] coded y,uvDC,uvAC intra: 53.0% 55.5% 18.1% inter: 10.7% 12.9% 0.4%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] i16 v,h,dc,p: 35% 32% 23% 10%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 26% 26%  4%  4%  5%  5%  5%  5%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 26% 13%  5%  6%  7%  6%  5%  5%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] i8c dc,h,v,p: 46% 28% 20%  6%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] Weighted P-Frames: Y:1.0% UV:0.3%
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.713] [info]    [ffmpeg] [libx264 @ 000002B1381A7880] kb/s:9453.27
[2022-05-15 09:23:47.713] [info]    
[2022-05-15 09:23:47.879] [info]    ffmpeg[ch2/20220515085347.mp4] Uninitialized.
[2022-05-15 09:53:17.623] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515092317.mp4\r\n
[2022-05-15 09:53:17.624] [info]    ffmpeg[ch1/20220515092317.mp4] Uninitialized.
[2022-05-15 09:53:17.624] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 09:53:17.627] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515095317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 09:53:17.628] [info]    ffmpeg[ch1/20220515095317.mp4] Initialized.
[2022-05-15 09:53:17.628] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 09:53:17.637] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] using SAR=1/1
[2022-05-15 09:53:17.637] [info]    
[2022-05-15 09:53:17.638] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 09:53:17.638] [info]    
[2022-05-15 09:53:17.645] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 09:53:17.645] [info]    
[2022-05-15 09:53:17.650] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D0340] Pure channel mapping detected:
[2022-05-15 09:53:17.650] [info]    [ffmpeg]  0
[2022-05-15 09:53:17.650] [info]    [ffmpeg]  1
[2022-05-15 09:53:17.650] [info]    [ffmpeg] 
[2022-05-15 09:53:17.650] [info]    
[2022-05-15 09:53:17.661] [warning] ffmpeg[ch1/20220515095317.mp4] Unused option s=1920:1080
[2022-05-15 09:53:17.715] [info]    [ffmpeg] [aac @ 000002B255504840] Qavg: 5357.390
[2022-05-15 09:53:17.715] [info]    
[2022-05-15 09:53:17.723] [info]    [ffmpeg] [libx264 @ 000002B195660740] frame I:360   Avg QP:29.11  size:114097
[2022-05-15 09:53:17.723] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] frame P:22722 Avg QP:16.04  size: 69912
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] frame B:66917 Avg QP:21.97  size:  9639
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] consecutive B-frames:  0.8%  0.3%  0.1% 98.9%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] mb I  I16..4: 39.8% 18.5% 41.7%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] mb P  I16..4:  2.3%  0.9%  1.4%  P16..4: 28.5%  6.5%  6.6%  0.0%  0.0%    skip:53.7%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  5.2%  2.2%  0.6%  direct: 5.1%  skip:86.5%  L0:35.5% L1:43.2% BI:21.3%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] 8x8 transform intra:20.9% inter:21.6%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] coded y,uvDC,uvAC intra: 55.0% 58.9% 40.1% inter: 9.5% 7.3% 2.7%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] i16 v,h,dc,p: 50% 39%  4%  6%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 26% 18%  5%  5%  6%  6%  5%  6%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 29% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] i8c dc,h,v,p: 36% 31% 27%  6%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.724] [info]    [ffmpeg] [libx264 @ 000002B195660740] kb/s:10109.52
[2022-05-15 09:53:17.724] [info]    
[2022-05-15 09:53:17.870] [info]    ffmpeg[ch1/20220515092317.mp4] Uninitialized.
[2022-05-15 09:53:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515092347.mp4\r\n
[2022-05-15 09:53:47.561] [info]    ffmpeg[ch2/20220515092347.mp4] Uninitialized.
[2022-05-15 09:53:47.561] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 09:53:47.564] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515095347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 09:53:47.564] [info]    ffmpeg[ch2/20220515095347.mp4] Initialized.
[2022-05-15 09:53:47.564] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 09:53:47.569] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] using SAR=1/1
[2022-05-15 09:53:47.569] [info]    
[2022-05-15 09:53:47.570] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 09:53:47.570] [info]    
[2022-05-15 09:53:47.577] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 09:53:47.577] [info]    
[2022-05-15 09:53:47.588] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1240] Pure channel mapping detected:
[2022-05-15 09:53:47.589] [info]    [ffmpeg]  0
[2022-05-15 09:53:47.589] [info]    [ffmpeg]  1
[2022-05-15 09:53:47.589] [info]    [ffmpeg] 
[2022-05-15 09:53:47.589] [info]    
[2022-05-15 09:53:47.594] [warning] ffmpeg[ch2/20220515095347.mp4] Unused option s=1920:1080
[2022-05-15 09:53:47.686] [info]    [ffmpeg] [aac @ 000002B15E74B500] Qavg: 333.515
[2022-05-15 09:53:47.686] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] frame I:381   Avg QP:22.60  size:102334
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] frame P:23434 Avg QP:17.82  size: 60840
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] frame B:66185 Avg QP:21.35  size: 10020
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] consecutive B-frames:  0.8%  3.1%  0.8% 95.3%
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] mb I  I16..4: 29.3% 41.7% 29.1%
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] mb P  I16..4:  9.3% 12.7%  2.9%  P16..4: 28.6% 11.0%  7.5%  0.0%  0.0%    skip:28.0%
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] mb B  I16..4:  1.6%  1.3%  0.1%  B16..8: 13.0%  3.7%  0.4%  direct: 9.1%  skip:70.8%  L0:45.5% L1:41.2% BI:13.2%
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.690] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] 8x8 transform intra:48.9% inter:28.8%
[2022-05-15 09:53:47.690] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] coded y,uvDC,uvAC intra: 58.6% 56.6% 22.4% inter: 9.9% 12.8% 1.5%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] i16 v,h,dc,p: 37% 28% 24% 11%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 20% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 24% 13%  5%  7%  7%  7%  6%  5%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] i8c dc,h,v,p: 47% 26% 22%  6%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] Weighted P-Frames: Y:0.1% UV:0.0%
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.691] [info]    [ffmpeg] [libx264 @ 000002B137E4CE40] kb/s:9457.32
[2022-05-15 09:53:47.691] [info]    
[2022-05-15 09:53:47.844] [info]    ffmpeg[ch2/20220515092347.mp4] Uninitialized.
[2022-05-15 10:23:17.625] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515095317.mp4\r\n
[2022-05-15 10:23:17.626] [info]    ffmpeg[ch1/20220515095317.mp4] Uninitialized.
[2022-05-15 10:23:17.626] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 10:23:17.629] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515102317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 10:23:17.629] [info]    ffmpeg[ch1/20220515102317.mp4] Initialized.
[2022-05-15 10:23:17.630] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 10:23:17.640] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] using SAR=1/1
[2022-05-15 10:23:17.640] [info]    
[2022-05-15 10:23:17.640] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 10:23:17.640] [info]    
[2022-05-15 10:23:17.648] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 10:23:17.648] [info]    
[2022-05-15 10:23:17.656] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4500] Pure channel mapping detected:
[2022-05-15 10:23:17.656] [info]    [ffmpeg]  0
[2022-05-15 10:23:17.656] [info]    [ffmpeg]  1
[2022-05-15 10:23:17.656] [info]    [ffmpeg] 
[2022-05-15 10:23:17.656] [info]    
[2022-05-15 10:23:17.664] [warning] ffmpeg[ch1/20220515102317.mp4] Unused option s=1920:1080
[2022-05-15 10:23:17.712] [info]    [ffmpeg] [aac @ 000002B255006D40] Qavg: 349.603
[2022-05-15 10:23:17.712] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] frame I:360   Avg QP:29.84  size:113636
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] frame P:22750 Avg QP:16.34  size: 70129
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] frame B:66890 Avg QP:22.41  size:  9755
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] consecutive B-frames:  0.7%  0.4%  0.2% 98.6%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] mb I  I16..4: 39.1% 19.0% 42.0%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] mb P  I16..4:  2.2%  0.9%  1.2%  P16..4: 29.0%  6.3%  6.6%  0.0%  0.0%    skip:53.8%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  4.9%  2.1%  0.6%  direct: 5.0%  skip:87.0%  L0:30.1% L1:47.6% BI:22.3%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] 8x8 transform intra:22.2% inter:21.0%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] coded y,uvDC,uvAC intra: 54.9% 58.9% 39.4% inter: 9.5% 7.2% 2.5%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] i16 v,h,dc,p: 52% 38%  4%  6%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 24% 17%  5%  5%  7%  5%  7%  6%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 10%  4%  6%  6%  5%  5%  5%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] i8c dc,h,v,p: 36% 30% 28%  6%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B15E932AC0] kb/s:10172.73
[2022-05-15 10:23:17.718] [info]    
[2022-05-15 10:23:17.858] [info]    ffmpeg[ch1/20220515095317.mp4] Uninitialized.
[2022-05-15 10:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515095347.mp4\r\n
[2022-05-15 10:23:47.559] [info]    ffmpeg[ch2/20220515095347.mp4] Uninitialized.
[2022-05-15 10:23:47.559] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 10:23:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515102347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 10:23:47.562] [info]    ffmpeg[ch2/20220515102347.mp4] Initialized.
[2022-05-15 10:23:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 10:23:47.568] [info]    [ffmpeg] [libx264 @ 000002B255030680] using SAR=1/1
[2022-05-15 10:23:47.568] [info]    
[2022-05-15 10:23:47.569] [info]    [ffmpeg] [libx264 @ 000002B255030680] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 10:23:47.569] [info]    
[2022-05-15 10:23:47.575] [info]    [ffmpeg] [libx264 @ 000002B255030680] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 10:23:47.575] [info]    
[2022-05-15 10:23:47.586] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4D00] Pure channel mapping detected:
[2022-05-15 10:23:47.586] [info]    [ffmpeg]  0
[2022-05-15 10:23:47.586] [info]    [ffmpeg]  1
[2022-05-15 10:23:47.586] [info]    [ffmpeg] 
[2022-05-15 10:23:47.586] [info]    
[2022-05-15 10:23:47.591] [warning] ffmpeg[ch2/20220515102347.mp4] Unused option s=1920:1080
[2022-05-15 10:23:47.683] [info]    [ffmpeg] [aac @ 000002B195221F80] Qavg: 311.825
[2022-05-15 10:23:47.683] [info]    
[2022-05-15 10:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] frame I:379   Avg QP:24.51  size:103857
[2022-05-15 10:23:47.689] [info]    
[2022-05-15 10:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] frame P:24064 Avg QP:18.88  size: 60171
[2022-05-15 10:23:47.689] [info]    
[2022-05-15 10:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] frame B:65557 Avg QP:22.92  size:  9823
[2022-05-15 10:23:47.689] [info]    
[2022-05-15 10:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] consecutive B-frames:  1.0%  4.6%  2.9% 91.5%
[2022-05-15 10:23:47.689] [info]    
[2022-05-15 10:23:47.689] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] mb I  I16..4: 25.6% 43.3% 31.1%
[2022-05-15 10:23:47.689] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] mb P  I16..4:  7.9% 12.4%  2.9%  P16..4: 30.0% 11.2%  8.0%  0.0%  0.0%    skip:27.6%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] mb B  I16..4:  1.6%  1.7%  0.1%  B16..8: 11.8%  3.7%  0.4%  direct: 8.2%  skip:72.6%  L0:42.0% L1:42.4% BI:15.5%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] 8x8 transform intra:51.9% inter:28.4%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] coded y,uvDC,uvAC intra: 54.9% 54.7% 18.7% inter: 10.8% 9.8% 0.8%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] i16 v,h,dc,p: 34% 33% 23% 10%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 24% 27%  5%  5%  5%  5%  5%  5%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 26% 13%  5%  7%  7%  7%  6%  5%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] i8c dc,h,v,p: 47% 28% 20%  6%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] Weighted P-Frames: Y:0.9% UV:0.2%
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.690] [info]    [ffmpeg] [libx264 @ 000002B1952589C0] kb/s:9472.28
[2022-05-15 10:23:47.690] [info]    
[2022-05-15 10:23:47.847] [info]    ffmpeg[ch2/20220515095347.mp4] Uninitialized.
[2022-05-15 10:53:17.633] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515102317.mp4\r\n
[2022-05-15 10:53:17.634] [info]    ffmpeg[ch1/20220515102317.mp4] Uninitialized.
[2022-05-15 10:53:17.634] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 10:53:17.639] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515105317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 10:53:17.640] [info]    ffmpeg[ch1/20220515105317.mp4] Initialized.
[2022-05-15 10:53:17.640] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 10:53:17.647] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] using SAR=1/1
[2022-05-15 10:53:17.647] [info]    
[2022-05-15 10:53:17.647] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 10:53:17.647] [info]    
[2022-05-15 10:53:17.652] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 10:53:17.652] [info]    
[2022-05-15 10:53:17.659] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7CFC40] Pure channel mapping detected:
[2022-05-15 10:53:17.659] [info]    [ffmpeg]  0
[2022-05-15 10:53:17.659] [info]    [ffmpeg]  1
[2022-05-15 10:53:17.659] [info]    [ffmpeg] 
[2022-05-15 10:53:17.659] [info]    
[2022-05-15 10:53:17.664] [warning] ffmpeg[ch1/20220515105317.mp4] Unused option s=1920:1080
[2022-05-15 10:53:17.734] [info]    [ffmpeg] [aac @ 000002B1FB5B5D80] Qavg: 897.392
[2022-05-15 10:53:17.734] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] frame I:360   Avg QP:28.87  size:114367
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] frame P:22720 Avg QP:15.83  size: 69177
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] frame B:66920 Avg QP:21.75  size:  9611
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] consecutive B-frames:  0.8%  0.2%  0.2% 98.8%
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] mb I  I16..4: 40.3% 17.9% 41.8%
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] mb P  I16..4:  2.1%  0.8%  1.1%  P16..4: 28.9%  6.0%  6.3%  0.0%  0.0%    skip:54.8%
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  4.6%  2.1%  0.6%  direct: 5.0%  skip:87.2%  L0:34.8% L1:42.4% BI:22.8%
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.740] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] 8x8 transform intra:21.1% inter:21.4%
[2022-05-15 10:53:17.740] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] coded y,uvDC,uvAC intra: 55.7% 59.9% 42.9% inter: 9.5% 7.0% 2.5%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] i16 v,h,dc,p: 52% 37%  5%  6%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 22% 21%  5%  5%  5%  5%  6%  5%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 29% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] i8c dc,h,v,p: 35% 30% 28%  6%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.741] [info]    [ffmpeg] [libx264 @ 000002B194F24E00] kb/s:10026.79
[2022-05-15 10:53:17.741] [info]    
[2022-05-15 10:53:17.882] [info]    ffmpeg[ch1/20220515102317.mp4] Uninitialized.
[2022-05-15 10:53:47.559] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515102347.mp4\r\n
[2022-05-15 10:53:47.560] [info]    ffmpeg[ch2/20220515102347.mp4] Uninitialized.
[2022-05-15 10:53:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 10:53:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515105347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 10:53:47.562] [info]    ffmpeg[ch2/20220515105347.mp4] Initialized.
[2022-05-15 10:53:47.562] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 10:53:47.569] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] using SAR=1/1
[2022-05-15 10:53:47.569] [info]    
[2022-05-15 10:53:47.569] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 10:53:47.569] [info]    
[2022-05-15 10:53:47.574] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 10:53:47.574] [info]    
[2022-05-15 10:53:47.583] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B15E7D1940] Pure channel mapping detected:
[2022-05-15 10:53:47.583] [info]    [ffmpeg]  0
[2022-05-15 10:53:47.583] [info]    [ffmpeg]  1
[2022-05-15 10:53:47.583] [info]    [ffmpeg] 
[2022-05-15 10:53:47.583] [info]    
[2022-05-15 10:53:47.589] [warning] ffmpeg[ch2/20220515105347.mp4] Unused option s=1920:1080
[2022-05-15 10:53:47.657] [info]    [ffmpeg] [aac @ 000002B254BFECC0] Qavg: 482.155
[2022-05-15 10:53:47.657] [info]    
[2022-05-15 10:53:47.664] [info]    [ffmpeg] [libx264 @ 000002B255030680] frame I:389   Avg QP:23.70  size:102952
[2022-05-15 10:53:47.664] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] frame P:23742 Avg QP:19.57  size: 58478
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] frame B:65869 Avg QP:22.66  size: 10757
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] consecutive B-frames:  1.3%  3.1%  1.0% 94.6%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] mb I  I16..4: 28.0% 43.9% 28.2%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] mb P  I16..4: 11.7% 16.7%  3.1%  P16..4: 27.4% 11.7%  7.2%  0.0%  0.0%    skip:22.2%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] mb B  I16..4:  2.1%  2.0%  0.1%  B16..8: 14.7%  4.5%  0.4%  direct: 9.4%  skip:66.8%  L0:46.2% L1:40.6% BI:13.2%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] 8x8 transform intra:51.2% inter:28.1%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] coded y,uvDC,uvAC intra: 53.2% 55.3% 18.1% inter: 10.3% 12.1% 0.5%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] i16 v,h,dc,p: 37% 29% 23% 11%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 21% 25%  4%  5%  6%  5%  5%  5%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 24% 13%  5%  7%  8%  6%  5%  5%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] i8c dc,h,v,p: 46% 26% 22%  6%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] Weighted P-Frames: Y:0.7% UV:0.4%
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.665] [info]    [ffmpeg] [libx264 @ 000002B255030680] kb/s:9497.88
[2022-05-15 10:53:47.665] [info]    
[2022-05-15 10:53:47.817] [info]    ffmpeg[ch2/20220515102347.mp4] Uninitialized.
[2022-05-15 11:23:17.627] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515105317.mp4\r\n
[2022-05-15 11:23:17.629] [info]    ffmpeg[ch1/20220515105317.mp4] Uninitialized.
[2022-05-15 11:23:17.630] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 11:23:17.633] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515112317.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:23:17.634] [info]    ffmpeg[ch1/20220515112317.mp4] Initialized.
[2022-05-15 11:23:17.634] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:23:17.641] [info]    [ffmpeg] [libx264 @ 000002B13801FF40] using SAR=1/1
[2022-05-15 11:23:17.641] [info]    
[2022-05-15 11:23:17.641] [info]    [ffmpeg] [libx264 @ 000002B13801FF40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:23:17.641] [info]    
[2022-05-15 11:23:17.648] [info]    [ffmpeg] [libx264 @ 000002B13801FF40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:23:17.648] [info]    
[2022-05-15 11:23:17.658] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D4800] Pure channel mapping detected:
[2022-05-15 11:23:17.658] [info]    [ffmpeg]  0
[2022-05-15 11:23:17.658] [info]    [ffmpeg]  1
[2022-05-15 11:23:17.658] [info]    [ffmpeg] 
[2022-05-15 11:23:17.658] [info]    
[2022-05-15 11:23:17.663] [warning] ffmpeg[ch1/20220515112317.mp4] Unused option s=1920:1080
[2022-05-15 11:23:17.712] [info]    [ffmpeg] [aac @ 000002B1FF265140] Qavg: 9409.839
[2022-05-15 11:23:17.712] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] frame I:360   Avg QP:24.81  size:111177
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] frame P:22696 Avg QP:14.08  size: 66908
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] frame B:66943 Avg QP:19.25  size:  8884
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] consecutive B-frames:  0.8%  0.1%  0.0% 99.1%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] mb I  I16..4: 46.5% 15.7% 37.8%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] mb P  I16..4:  2.0%  1.0%  1.1%  P16..4: 27.0%  5.7%  5.4%  0.0%  0.0%    skip:57.8%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  5.5%  2.3%  0.5%  direct: 5.0%  skip:86.4%  L0:42.9% L1:38.0% BI:19.1%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] 8x8 transform intra:22.7% inter:22.9%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] coded y,uvDC,uvAC intra: 57.9% 58.5% 43.2% inter: 9.6% 5.8% 2.1%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] i16 v,h,dc,p: 51% 36%  5%  7%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 24% 22%  4%  5%  5%  5%  5%  5%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 29% 10%  4%  6%  5%  6%  5%  5%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] i8c dc,h,v,p: 37% 30% 27%  5%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.718] [info]    [ffmpeg] [libx264 @ 000002B1FEC28240] kb/s:9570.17
[2022-05-15 11:23:17.718] [info]    
[2022-05-15 11:23:17.857] [info]    ffmpeg[ch1/20220515105317.mp4] Uninitialized.
[2022-05-15 11:23:47.558] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515105347.mp4\r\n
[2022-05-15 11:23:47.560] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 11:23:47.560] [info]    ffmpeg[ch2/20220515105347.mp4] Uninitialized.
[2022-05-15 11:23:47.561] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515112347.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:23:47.561] [info]    ffmpeg[ch2/20220515112347.mp4] Initialized.
[2022-05-15 11:23:47.561] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:23:47.567] [info]    [ffmpeg] [libx264 @ 000002B195747580] using SAR=1/1
[2022-05-15 11:23:47.567] [info]    
[2022-05-15 11:23:47.567] [info]    [ffmpeg] [libx264 @ 000002B195747580] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:23:47.567] [info]    
[2022-05-15 11:23:47.573] [info]    [ffmpeg] [libx264 @ 000002B195747580] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:23:47.573] [info]    
[2022-05-15 11:23:47.581] [info]    [ffmpeg] [Parsed_pan_0 @ 000002B1643D5900] Pure channel mapping detected:
[2022-05-15 11:23:47.581] [info]    [ffmpeg]  0
[2022-05-15 11:23:47.581] [info]    [ffmpeg]  1
[2022-05-15 11:23:47.581] [info]    [ffmpeg] 
[2022-05-15 11:23:47.581] [info]    
[2022-05-15 11:23:47.586] [warning] ffmpeg[ch2/20220515112347.mp4] Unused option s=1920:1080
[2022-05-15 11:23:47.691] [info]    [ffmpeg] [aac @ 000002B1FAFA8380] Qavg: 408.739
[2022-05-15 11:23:47.691] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] frame I:375   Avg QP:23.38  size:102779
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] frame P:23785 Avg QP:19.04  size: 58169
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] frame B:65840 Avg QP:22.31  size: 10515
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] consecutive B-frames:  1.1%  3.5%  1.4% 93.9%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] mb I  I16..4: 28.3% 44.2% 27.5%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] mb P  I16..4: 11.1% 15.7%  2.9%  P16..4: 28.1% 11.0%  6.9%  0.0%  0.0%    skip:24.3%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] mb B  I16..4:  2.0%  1.9%  0.1%  B16..8: 13.5%  4.2%  0.4%  direct: 9.6%  skip:68.5%  L0:42.4% L1:44.4% BI:13.2%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] 8x8 transform intra:51.3% inter:30.3%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] coded y,uvDC,uvAC intra: 53.8% 55.6% 18.4% inter: 10.4% 11.8% 0.6%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] i16 v,h,dc,p: 36% 30% 22% 11%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 23% 26%  4%  5%  6%  5%  5%  5%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 25% 13%  5%  7%  7%  6%  5%  5%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] i8c dc,h,v,p: 46% 27% 21%  6%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] Weighted P-Frames: Y:1.0% UV:0.2%
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.699] [info]    [ffmpeg] [libx264 @ 000002B194F84D40] kb/s:9397.45
[2022-05-15 11:23:47.699] [info]    
[2022-05-15 11:23:47.850] [info]    ffmpeg[ch2/20220515105347.mp4] Uninitialized.
[2022-05-15 11:28:47.475] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.03173
[2022-05-15 11:28:47.506] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.05173
[2022-05-15 11:28:47.664] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.07173
[2022-05-15 11:28:47.703] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.09173
[2022-05-15 11:28:47.898] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.11173
[2022-05-15 11:28:47.926] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.13173
[2022-05-15 11:28:48.265] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.15173
[2022-05-15 11:28:48.300] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.17173
[2022-05-15 11:28:48.585] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.19173
[2022-05-15 11:28:48.630] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.21173
[2022-05-15 11:28:48.784] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.23173
[2022-05-15 11:28:48.812] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.25173
[2022-05-15 11:28:52.737] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.27173
[2022-05-15 11:28:52.762] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.29173
[2022-05-15 11:28:55.944] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.31173
[2022-05-15 11:28:55.971] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.33173
[2022-05-15 11:28:56.186] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.35173
[2022-05-15 11:28:56.226] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.37173
[2022-05-15 11:28:56.473] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.39173
[2022-05-15 11:28:56.516] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.41173
[2022-05-15 11:28:59.097] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.43173
[2022-05-15 11:28:59.130] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.45173
[2022-05-15 11:28:59.436] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.47173
[2022-05-15 11:28:59.470] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.49173
[2022-05-15 11:28:59.631] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.51173
[2022-05-15 11:28:59.670] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.53173
[2022-05-15 11:28:59.821] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.55173
[2022-05-15 11:28:59.848] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.57173
[2022-05-15 11:29:00.228] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.59173
[2022-05-15 11:29:00.257] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.61173
[2022-05-15 11:29:00.453] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.63173
[2022-05-15 11:29:00.483] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.65173
[2022-05-15 11:29:04.070] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.67173
[2022-05-15 11:29:04.103] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.69173
[2022-05-15 11:29:04.349] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.71173
[2022-05-15 11:29:04.374] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.73173
[2022-05-15 11:29:04.585] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.75173
[2022-05-15 11:29:04.610] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.77173
[2022-05-15 11:29:10.264] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.79173
[2022-05-15 11:29:10.289] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.81173
[2022-05-15 11:29:10.693] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.83173
[2022-05-15 11:29:10.727] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.85173
[2022-05-15 11:29:10.951] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.87173
[2022-05-15 11:29:10.986] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.89173
[2022-05-15 11:29:11.219] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.91173
[2022-05-15 11:29:11.251] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.93173
[2022-05-15 11:29:11.609] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.95173
[2022-05-15 11:29:11.632] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.97173
[2022-05-15 11:29:11.782] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 1.99173
[2022-05-15 11:29:11.822] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.01173
[2022-05-15 11:29:12.031] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.03173
[2022-05-15 11:29:12.067] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.05173
[2022-05-15 11:29:12.633] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.07173
[2022-05-15 11:29:12.670] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.09173
[2022-05-15 11:29:12.818] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.11173
[2022-05-15 11:29:12.840] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.13173
[2022-05-15 11:29:15.225] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.15173
[2022-05-15 11:29:15.262] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.17173
[2022-05-15 11:29:15.718] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.19173
[2022-05-15 11:29:15.783] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.21173
[2022-05-15 11:29:15.840] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.23173
[2022-05-15 11:29:15.882] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.25173
[2022-05-15 11:29:15.994] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.27173
[2022-05-15 11:29:16.026] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.29173
[2022-05-15 11:29:16.226] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.31173
[2022-05-15 11:29:16.260] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.33173
[2022-05-15 11:29:16.427] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.35173
[2022-05-15 11:29:16.461] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.37173
[2022-05-15 11:29:20.308] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.39173
[2022-05-15 11:29:20.342] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.41173
[2022-05-15 11:29:20.499] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.43173
[2022-05-15 11:29:20.527] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.45173
[2022-05-15 11:29:23.121] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.47173
[2022-05-15 11:29:23.151] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.49173
[2022-05-15 11:29:23.256] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.51173
[2022-05-15 11:29:23.289] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.53173
[2022-05-15 11:29:23.501] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.06
[2022-05-15 11:29:23.527] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.08
[2022-05-15 11:29:23.565] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.55173
[2022-05-15 11:29:23.596] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.57173
[2022-05-15 11:29:23.612] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.0406667
[2022-05-15 11:29:23.704] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.59173
[2022-05-15 11:29:23.746] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.61173
[2022-05-15 11:29:23.897] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.63173
[2022-05-15 11:29:23.899] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.0606667
[2022-05-15 11:29:23.924] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.65173
[2022-05-15 11:29:23.925] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.0806667
[2022-05-15 11:29:24.264] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.100667
[2022-05-15 11:29:24.278] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.67173
[2022-05-15 11:29:24.290] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.120667
[2022-05-15 11:29:24.307] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.69173
[2022-05-15 11:29:31.067] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.71173
[2022-05-15 11:29:31.113] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.73173
[2022-05-15 11:29:31.235] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.75173
[2022-05-15 11:29:31.265] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.77173
[2022-05-15 11:29:31.589] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.79173
[2022-05-15 11:29:31.611] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.81173
[2022-05-15 11:29:31.902] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.83173
[2022-05-15 11:29:31.930] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.85173
[2022-05-15 11:29:34.432] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.87173
[2022-05-15 11:29:34.466] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.89173
[2022-05-15 11:29:34.674] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.91173
[2022-05-15 11:29:34.708] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.93173
[2022-05-15 11:29:34.896] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.140667
[2022-05-15 11:29:34.912] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.95173
[2022-05-15 11:29:34.931] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.160667
[2022-05-15 11:29:34.944] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.97173
[2022-05-15 11:29:35.107] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 2.99173
[2022-05-15 11:29:35.144] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.01173
[2022-05-15 11:29:35.225] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.03173
[2022-05-15 11:29:35.252] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.05173
[2022-05-15 11:29:35.262] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.180667
[2022-05-15 11:29:35.291] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.200667
[2022-05-15 11:29:35.543] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.07173
[2022-05-15 11:29:35.587] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.09173
[2022-05-15 11:29:35.669] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.220667
[2022-05-15 11:29:35.700] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.240667
[2022-05-15 11:29:35.777] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.11173
[2022-05-15 11:29:35.812] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.13173
[2022-05-15 11:29:36.631] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.260667
[2022-05-15 11:29:36.666] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.280667
[2022-05-15 11:29:36.746] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.15173
[2022-05-15 11:29:36.809] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.17173
[2022-05-15 11:29:36.819] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.300667
[2022-05-15 11:29:36.861] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.320667
[2022-05-15 11:29:36.867] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.19173
[2022-05-15 11:29:36.899] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.21173
[2022-05-15 11:29:37.075] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.23173
[2022-05-15 11:29:37.108] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.25173
[2022-05-15 11:29:37.147] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.340667
[2022-05-15 11:29:37.190] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.360667
[2022-05-15 11:29:37.262] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.27173
[2022-05-15 11:29:37.304] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.29173
[2022-05-15 11:29:37.344] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.380667
[2022-05-15 11:29:37.373] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.400667
[2022-05-15 11:29:37.471] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.31173
[2022-05-15 11:29:37.502] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.33173
[2022-05-15 11:29:37.671] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.420667
[2022-05-15 11:29:37.708] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.35173
[2022-05-15 11:29:37.709] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.440667
[2022-05-15 11:29:37.741] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.37173
[2022-05-15 11:29:37.909] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.460667
[2022-05-15 11:29:37.944] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.480667
[2022-05-15 11:29:37.989] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.39173
[2022-05-15 11:29:38.023] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.41173
[2022-05-15 11:29:38.140] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.500667
[2022-05-15 11:29:38.166] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.520667
[2022-05-15 11:29:38.177] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.43173
[2022-05-15 11:29:38.210] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.45173
[2022-05-15 11:29:38.338] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.47173
[2022-05-15 11:29:38.372] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.49173
[2022-05-15 11:29:38.541] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.540667
[2022-05-15 11:29:38.567] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.560667
[2022-05-15 11:29:38.840] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.51173
[2022-05-15 11:29:38.863] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.580667
[2022-05-15 11:29:38.871] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.53173
[2022-05-15 11:29:38.903] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.600667
[2022-05-15 11:29:38.994] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.55173
[2022-05-15 11:29:39.040] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.57173
[2022-05-15 11:29:39.303] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.59173
[2022-05-15 11:29:39.334] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.61173
[2022-05-15 11:29:39.391] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.620667
[2022-05-15 11:29:39.435] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.640667
[2022-05-15 11:29:39.493] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.660667
[2022-05-15 11:29:39.534] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.680667
[2022-05-15 11:29:39.636] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.63173
[2022-05-15 11:29:39.690] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.65173
[2022-05-15 11:29:39.750] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.67173
[2022-05-15 11:29:39.781] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.700667
[2022-05-15 11:29:39.787] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.69173
[2022-05-15 11:29:39.811] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.720667
[2022-05-15 11:29:39.947] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.71173
[2022-05-15 11:29:39.988] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.73173
[2022-05-15 11:29:40.020] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.740667
[2022-05-15 11:29:40.052] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.760667
[2022-05-15 11:29:43.219] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.780667
[2022-05-15 11:29:43.244] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.800667
[2022-05-15 11:29:43.310] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.75173
[2022-05-15 11:29:43.336] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.77173
[2022-05-15 11:29:43.627] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.79173
[2022-05-15 11:29:43.662] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.81173
[2022-05-15 11:29:43.747] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.820667
[2022-05-15 11:29:43.776] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.840667
[2022-05-15 11:29:43.991] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.83173
[2022-05-15 11:29:44.030] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.85173
[2022-05-15 11:29:44.062] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.860667
[2022-05-15 11:29:44.101] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.880667
[2022-05-15 11:29:44.188] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.87173
[2022-05-15 11:29:44.212] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.89173
[2022-05-15 11:29:54.902] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.91173
[2022-05-15 11:29:54.927] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.93173
[2022-05-15 11:29:55.228] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.95173
[2022-05-15 11:29:55.262] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.97173
[2022-05-15 11:30:01.326] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 3.99173
[2022-05-15 11:30:01.362] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.01173
[2022-05-15 11:30:01.431] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.03173
[2022-05-15 11:30:01.470] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.05173
[2022-05-15 11:30:01.668] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.07173
[2022-05-15 11:30:01.691] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.09173
[2022-05-15 11:30:01.976] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.11173
[2022-05-15 11:30:02.003] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.13173
[2022-05-15 11:30:02.176] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.15173
[2022-05-15 11:30:02.203] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.17173
[2022-05-15 11:30:02.434] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.19173
[2022-05-15 11:30:02.466] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.21173
[2022-05-15 11:30:02.698] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.23173
[2022-05-15 11:30:02.729] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.25173
[2022-05-15 11:30:03.107] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.27173
[2022-05-15 11:30:03.129] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.29173
[2022-05-15 11:30:06.217] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.31173
[2022-05-15 11:30:06.252] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.33173
[2022-05-15 11:30:06.489] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.35173
[2022-05-15 11:30:06.519] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.37173
[2022-05-15 11:30:06.620] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.39173
[2022-05-15 11:30:06.662] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.41173
[2022-05-15 11:30:07.144] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.43173
[2022-05-15 11:30:07.167] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.45173
[2022-05-15 11:30:11.147] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.47173
[2022-05-15 11:30:11.172] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.49173
[2022-05-15 11:30:15.064] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.51173
[2022-05-15 11:30:15.097] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.53173
[2022-05-15 11:30:21.709] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.55173
[2022-05-15 11:30:21.749] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.57173
[2022-05-15 11:30:21.917] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.59173
[2022-05-15 11:30:21.949] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.61173
[2022-05-15 11:30:22.132] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.63173
[2022-05-15 11:30:22.164] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.65173
[2022-05-15 11:30:22.545] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.67173
[2022-05-15 11:30:22.566] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.69173
[2022-05-15 11:30:24.866] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.71173
[2022-05-15 11:30:24.893] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.73173
[2022-05-15 11:30:25.151] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.75173
[2022-05-15 11:30:25.189] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.77173
[2022-05-15 11:30:25.348] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.79173
[2022-05-15 11:30:25.375] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.81173
[2022-05-15 11:30:25.624] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.83173
[2022-05-15 11:30:25.664] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.85173
[2022-05-15 11:30:25.781] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.87173
[2022-05-15 11:30:25.819] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.89173
[2022-05-15 11:30:26.072] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.91173
[2022-05-15 11:30:26.103] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.93173
[2022-05-15 11:30:26.230] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.95173
[2022-05-15 11:30:26.260] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.97173
[2022-05-15 11:30:26.547] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 4.99173
[2022-05-15 11:30:26.577] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.01173
[2022-05-15 11:30:29.283] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.03173
[2022-05-15 11:30:29.318] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.05173
[2022-05-15 11:30:29.408] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.07173
[2022-05-15 11:30:29.463] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.09173
[2022-05-15 11:30:29.519] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.11173
[2022-05-15 11:30:29.551] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.13173
[2022-05-15 11:30:29.747] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.15173
[2022-05-15 11:30:29.782] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.17173
[2022-05-15 11:30:29.944] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.19173
[2022-05-15 11:30:29.976] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.21173
[2022-05-15 11:30:30.221] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.23173
[2022-05-15 11:30:30.248] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.25173
[2022-05-15 11:30:30.468] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.27173
[2022-05-15 11:30:30.500] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.29173
[2022-05-15 11:30:34.186] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.31173
[2022-05-15 11:30:34.211] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.33173
[2022-05-15 11:30:34.532] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.35173
[2022-05-15 11:30:34.557] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.37173
[2022-05-15 11:30:37.297] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.39173
[2022-05-15 11:30:37.331] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.41173
[2022-05-15 11:30:37.752] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.43173
[2022-05-15 11:30:37.782] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.45173
[2022-05-15 11:30:37.987] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.47173
[2022-05-15 11:30:38.025] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.49173
[2022-05-15 11:30:38.187] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.51173
[2022-05-15 11:30:38.218] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.53173
[2022-05-15 11:30:45.054] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.55173
[2022-05-15 11:30:45.094] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.57173
[2022-05-15 11:30:45.342] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.59173
[2022-05-15 11:30:45.370] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.61173
[2022-05-15 11:30:45.875] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.63173
[2022-05-15 11:30:45.903] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.65173
[2022-05-15 11:30:48.204] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.67173
[2022-05-15 11:30:48.233] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.69173
[2022-05-15 11:30:48.775] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.71173
[2022-05-15 11:30:48.805] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.73173
[2022-05-15 11:30:49.266] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.75173
[2022-05-15 11:30:49.302] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.77173
[2022-05-15 11:30:49.540] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.79173
[2022-05-15 11:30:49.582] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.81173
[2022-05-15 11:30:52.081] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.83173
[2022-05-15 11:30:52.114] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.85173
[2022-05-15 11:30:52.265] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.87173
[2022-05-15 11:30:52.292] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.89173
[2022-05-15 11:30:52.539] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.91173
[2022-05-15 11:30:52.567] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.93173
[2022-05-15 11:30:52.953] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.95173
[2022-05-15 11:30:52.984] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.97173
[2022-05-15 11:30:53.245] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 5.99173
[2022-05-15 11:30:53.270] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.01173
[2022-05-15 11:30:53.353] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.900667
[2022-05-15 11:30:53.384] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.920667
[2022-05-15 11:30:55.194] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.03173
[2022-05-15 11:30:55.225] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.05173
[2022-05-15 11:30:55.416] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.07173
[2022-05-15 11:30:55.451] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.09173
[2022-05-15 11:30:55.662] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.940667
[2022-05-15 11:30:55.690] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.960667
[2022-05-15 11:30:55.710] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.11173
[2022-05-15 11:30:55.739] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.13173
[2022-05-15 11:30:55.952] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 0.980667
[2022-05-15 11:30:55.986] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.00067
[2022-05-15 11:30:56.030] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.15173
[2022-05-15 11:30:56.061] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.17173
[2022-05-15 11:30:56.170] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.02067
[2022-05-15 11:30:56.204] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.04067
[2022-05-15 11:30:56.312] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.19173
[2022-05-15 11:30:56.352] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.21173
[2022-05-15 11:30:56.497] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.23173
[2022-05-15 11:30:56.532] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.25173
[2022-05-15 11:30:56.548] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.06067
[2022-05-15 11:30:56.580] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.08067
[2022-05-15 11:30:56.776] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.10067
[2022-05-15 11:30:56.806] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.12067
[2022-05-15 11:30:57.030] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.27173
[2022-05-15 11:30:57.056] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.29173
[2022-05-15 11:30:57.185] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.14067
[2022-05-15 11:30:57.220] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.16067
[2022-05-15 11:30:57.263] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.31173
[2022-05-15 11:30:57.301] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.33173
[2022-05-15 11:30:57.334] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.18067
[2022-05-15 11:30:57.373] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.20067
[2022-05-15 11:30:57.539] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.35173
[2022-05-15 11:30:57.563] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.37173
[2022-05-15 11:30:58.981] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.39173
[2022-05-15 11:30:59.023] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.41173
[2022-05-15 11:30:59.185] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.43173
[2022-05-15 11:30:59.211] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.45173
[2022-05-15 11:30:59.465] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.22067
[2022-05-15 11:30:59.494] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.24067
[2022-05-15 11:30:59.502] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.47173
[2022-05-15 11:30:59.532] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.49173
[2022-05-15 11:30:59.680] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.26067
[2022-05-15 11:30:59.706] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.28067
[2022-05-15 11:30:59.792] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.51173
[2022-05-15 11:30:59.824] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.53173
[2022-05-15 11:30:59.853] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.30067
[2022-05-15 11:30:59.900] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.32067
[2022-05-15 11:31:00.085] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.55173
[2022-05-15 11:31:00.108] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.57173
[2022-05-15 11:31:00.139] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.34067
[2022-05-15 11:31:00.179] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.36067
[2022-05-15 11:31:00.237] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.59173
[2022-05-15 11:31:00.269] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.61173
[2022-05-15 11:31:00.440] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.38067
[2022-05-15 11:31:00.470] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.40067
[2022-05-15 11:31:00.615] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.42067
[2022-05-15 11:31:00.620] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.63173
[2022-05-15 11:31:00.649] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.65173
[2022-05-15 11:31:00.649] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.44067
[2022-05-15 11:31:00.994] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.67173
[2022-05-15 11:31:01.020] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.46067
[2022-05-15 11:31:01.045] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.69173
[2022-05-15 11:31:01.051] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.48067
[2022-05-15 11:31:01.109] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.71173
[2022-05-15 11:31:01.136] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.73173
[2022-05-15 11:31:01.417] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.75173
[2022-05-15 11:31:01.448] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.77173
[2022-05-15 11:31:01.505] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.50067
[2022-05-15 11:31:01.532] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.52067
[2022-05-15 11:31:01.739] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.79173
[2022-05-15 11:31:01.757] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.81173
[2022-05-15 11:31:03.285] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.83173
[2022-05-15 11:31:03.318] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.85173
[2022-05-15 11:31:03.437] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.54067
[2022-05-15 11:31:03.460] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.56067
[2022-05-15 11:31:03.588] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.87173
[2022-05-15 11:31:03.623] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.89173
[2022-05-15 11:31:03.670] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.58067
[2022-05-15 11:31:03.703] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.60067
[2022-05-15 11:31:03.862] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.91173
[2022-05-15 11:31:03.874] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.62067
[2022-05-15 11:31:03.891] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.93173
[2022-05-15 11:31:03.908] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.64067
[2022-05-15 11:31:04.111] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.66067
[2022-05-15 11:31:04.156] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.68067
[2022-05-15 11:31:04.209] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.95173
[2022-05-15 11:31:04.226] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.70067
[2022-05-15 11:31:04.255] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.97173
[2022-05-15 11:31:04.257] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.72067
[2022-05-15 11:31:04.318] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 6.99173
[2022-05-15 11:31:04.356] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.01173
[2022-05-15 11:31:04.463] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.03173
[2022-05-15 11:31:04.507] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.05173
[2022-05-15 11:31:04.623] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.74067
[2022-05-15 11:31:04.663] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.76067
[2022-05-15 11:31:04.676] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.07173
[2022-05-15 11:31:04.710] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.09173
[2022-05-15 11:31:04.872] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.11173
[2022-05-15 11:31:04.875] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.78067
[2022-05-15 11:31:04.904] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.13173
[2022-05-15 11:31:04.911] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.80067
[2022-05-15 11:31:05.069] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.15173
[2022-05-15 11:31:05.082] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.82067
[2022-05-15 11:31:05.100] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.17173
[2022-05-15 11:31:05.111] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.84067
[2022-05-15 11:31:05.254] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.19173
[2022-05-15 11:31:05.296] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.21173
[2022-05-15 11:31:05.341] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.86067
[2022-05-15 11:31:05.368] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.88067
[2022-05-15 11:31:08.637] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.23173
[2022-05-15 11:31:08.683] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.25173
[2022-05-15 11:31:08.738] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.27173
[2022-05-15 11:31:08.774] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.29173
[2022-05-15 11:31:09.270] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.31173
[2022-05-15 11:31:09.296] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.90067
[2022-05-15 11:31:09.300] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.33173
[2022-05-15 11:31:09.342] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 1.92067
[2022-05-15 11:31:09.457] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.35173
[2022-05-15 11:31:09.476] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 7.37173
[2022-05-15 11:31:45.056] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (1 connections).
[2022-05-15 11:31:45.057] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (0 connections).
[2022-05-15 11:33:32.215] [info]    ############################################################################
[2022-05-15 11:33:32.216] [info]    CasparCG Server is distributed by the Swedish Broadcasting Corporation (SVT)
[2022-05-15 11:33:32.216] [info]    under the GNU General Public License GPLv3 or higher.
[2022-05-15 11:33:32.216] [info]    Please see LICENSE.TXT for details.
[2022-05-15 11:33:32.216] [info]    http://www.casparcg.com/
[2022-05-15 11:33:32.216] [info]    ############################################################################
[2022-05-15 11:33:32.216] [info]    Starting CasparCG Video and Graphics Playout Server 2.3.3 d6f06dab Dev
[2022-05-15 11:33:32.353] [info]    Initializing OpenGL Device.
[2022-05-15 11:33:32.356] [info]    Initialized OpenGL 4.5.0 NVIDIA 472.08 NVIDIA Corporation
[2022-05-15 11:33:32.357] [info]    Initialized image module.
[2022-05-15 11:33:32.358] [info]    Initialized ffmpeg module.
[2022-05-15 11:33:32.358] [info]    Initialized oal module.
[2022-05-15 11:33:32.358] [info]    Initialized decklink module.
[2022-05-15 11:33:32.358] [info]    Initialized screen module.
[2022-05-15 11:33:32.358] [info]    Initialized newtek module.
[2022-05-15 11:33:32.574] [info]    Initialized html module.
[2022-05-15 11:33:32.574] [info]    Flash support is disabled
[2022-05-15 11:33:32.574] [info]    Initialized flash module.
[2022-05-15 11:33:32.575] [info]    Initialized bluefish module.
[2022-05-15 11:33:32.575] [info]    "C:/CasparCG Server 2.3.3\casparcg.config":
[2022-05-15 11:33:32.575] [info]    -----------------------------------------
[2022-05-15 11:33:32.575] [info]    <?xml version="1.0" encoding="utf-8"?>
[2022-05-15 11:33:32.575] [info]    <configuration>
[2022-05-15 11:33:32.575] [info]       <paths>
[2022-05-15 11:33:32.575] [info]          <media-path>d:/casparcg/_media\</media-path>
[2022-05-15 11:33:32.575] [info]          <log-path>log\</log-path>
[2022-05-15 11:33:32.575] [info]          <data-path>data\</data-path>
[2022-05-15 11:33:32.575] [info]          <template-path>c:/casparcg\</template-path>
[2022-05-15 11:33:32.575] [info]          <thumbnails-path>thumbnails\</thumbnails-path>
[2022-05-15 11:33:32.575] [info]       </paths>
[2022-05-15 11:33:32.575] [info]       <channels>
[2022-05-15 11:33:32.575] [info]          <channel>
[2022-05-15 11:33:32.575] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:33:32.575] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:33:32.575] [info]             <consumers>
[2022-05-15 11:33:32.575] [info]                <screen>
[2022-05-15 11:33:32.575] [info]                   <device>1</device>
[2022-05-15 11:33:32.575] [info]                </screen>
[2022-05-15 11:33:32.575] [info]                <system-audio/>
[2022-05-15 11:33:32.575] [info]             </consumers>
[2022-05-15 11:33:32.575] [info]          </channel>
[2022-05-15 11:33:32.575] [info]          <channel>
[2022-05-15 11:33:32.575] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:33:32.575] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:33:32.575] [info]             <consumers>
[2022-05-15 11:33:32.575] [info]                <screen>
[2022-05-15 11:33:32.575] [info]                   <device>1</device>
[2022-05-15 11:33:32.575] [info]                </screen>
[2022-05-15 11:33:32.575] [info]                <system-audio/>
[2022-05-15 11:33:32.575] [info]             </consumers>
[2022-05-15 11:33:32.575] [info]          </channel>
[2022-05-15 11:33:32.575] [info]          <channel>
[2022-05-15 11:33:32.575] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:33:32.575] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:33:32.575] [info]             <consumers>
[2022-05-15 11:33:32.575] [info]                <screen>
[2022-05-15 11:33:32.575] [info]                   <device>1</device>
[2022-05-15 11:33:32.575] [info]                </screen>
[2022-05-15 11:33:32.575] [info]                <system-audio/>
[2022-05-15 11:33:32.575] [info]             </consumers>
[2022-05-15 11:33:32.575] [info]          </channel>
[2022-05-15 11:33:32.575] [info]          <channel>
[2022-05-15 11:33:32.575] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:33:32.575] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:33:32.575] [info]             <consumers>
[2022-05-15 11:33:32.575] [info]                <screen>
[2022-05-15 11:33:32.575] [info]                   <device>1</device>
[2022-05-15 11:33:32.575] [info]                </screen>
[2022-05-15 11:33:32.575] [info]                <system-audio/>
[2022-05-15 11:33:32.575] [info]             </consumers>
[2022-05-15 11:33:32.575] [info]          </channel>
[2022-05-15 11:33:32.575] [info]       </channels>
[2022-05-15 11:33:32.575] [info]       <controllers>
[2022-05-15 11:33:32.575] [info]          <tcp>
[2022-05-15 11:33:32.575] [info]             <port>5250</port>
[2022-05-15 11:33:32.575] [info]             <protocol>AMCP</protocol>
[2022-05-15 11:33:32.575] [info]          </tcp>
[2022-05-15 11:33:32.575] [info]       </controllers>
[2022-05-15 11:33:32.575] [info]       <osc>
[2022-05-15 11:33:32.575] [info]          <default-port>6250</default-port>
[2022-05-15 11:33:32.575] [info]          <predefined-clients>
[2022-05-15 11:33:32.575] [info]             <predefined-client>
[2022-05-15 11:33:32.575] [info]                <address>127.0.0.1</address>
[2022-05-15 11:33:32.575] [info]                <port>6251</port>
[2022-05-15 11:33:32.575] [info]             </predefined-client>
[2022-05-15 11:33:32.575] [info]             <predefined-client>
[2022-05-15 11:33:32.575] [info]                <address>127.0.0.1</address>
[2022-05-15 11:33:32.575] [info]                <port>6252</port>
[2022-05-15 11:33:32.575] [info]             </predefined-client>
[2022-05-15 11:33:32.575] [info]             <predefined-client>
[2022-05-15 11:33:32.575] [info]                <address>127.0.0.1</address>
[2022-05-15 11:33:32.575] [info]                <port>6253</port>
[2022-05-15 11:33:32.575] [info]             </predefined-client>
[2022-05-15 11:33:32.575] [info]             <predefined-client>
[2022-05-15 11:33:32.575] [info]                <address>127.0.0.1</address>
[2022-05-15 11:33:32.575] [info]                <port>6254</port>
[2022-05-15 11:33:32.575] [info]             </predefined-client>
[2022-05-15 11:33:32.575] [info]          </predefined-clients>
[2022-05-15 11:33:32.575] [info]       </osc>
[2022-05-15 11:33:32.575] [info]    </configuration>
[2022-05-15 11:33:32.575] [info]    -----------------------------------------
[2022-05-15 11:33:32.579] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 1
[2022-05-15 11:33:32.579] [info]    video_channel[1|1080i5000] Successfully Initialized.
[2022-05-15 11:33:32.579] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 2
[2022-05-15 11:33:32.579] [info]    video_channel[2|1080i5000] Successfully Initialized.
[2022-05-15 11:33:32.580] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 3
[2022-05-15 11:33:32.580] [info]    video_channel[3|1080i5000] Successfully Initialized.
[2022-05-15 11:33:32.580] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 4
[2022-05-15 11:33:32.580] [info]    video_channel[4|1080i5000] Successfully Initialized.
[2022-05-15 11:33:32.582] [info]    Screen consumer [1|1080i5000] Initialized.
[2022-05-15 11:33:32.713] [info]    oal[1|1080i5000] Initialized.
[2022-05-15 11:33:32.714] [info]    Screen consumer [2|1080i5000] Initialized.
[2022-05-15 11:33:32.715] [info]    oal[2|1080i5000] Initialized.
[2022-05-15 11:33:32.718] [info]    Screen consumer [3|1080i5000] Initialized.
[2022-05-15 11:33:32.718] [info]    oal[3|1080i5000] Initialized.
[2022-05-15 11:33:32.720] [info]    Screen consumer [4|1080i5000] Initialized.
[2022-05-15 11:33:32.720] [info]    oal[4|1080i5000] Initialized.
[2022-05-15 11:33:32.720] [info]    Initialized channels.
[2022-05-15 11:33:32.720] [info]    Initialized command repository.
[2022-05-15 11:33:32.720] [info]    Initialized startup producers.
[2022-05-15 11:33:32.725] [info]    Initialized controllers.
[2022-05-15 11:33:32.725] [info]    Initialized osc.
[2022-05-15 11:33:55.538] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (1 connections).
[2022-05-15 11:33:55.539] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (2 connections).
[2022-05-15 11:33:55.543] [info]    Received message from 127.0.0.1: VERSION SERVER\r\n
[2022-05-15 11:33:55.545] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:33:55.545] [info]    Received message from 127.0.0.1: VERSION FLASH\r\n
[2022-05-15 11:33:55.546] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:33:55.546] [info]    Received message from 127.0.0.1: VERSION TEMPLATEHOST\r\n
[2022-05-15 11:33:55.546] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:33:55.547] [info]    Received message from 127.0.0.1: info\r\n
[2022-05-15 11:33:55.547] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:33:55.550] [info]    Received message from 127.0.0.1: info paths\r\n
[2022-05-15 11:33:55.550] [info]    Sent message to 127.0.0.1:201 INFO PATHS OK\r\n<?xml version="1.0" encoding="utf-8"?>\n<paths>\n   <media-path>d:/casparcg/_media\</media-path>\n   <log-path>log\</log-path>\n   <data-path>data\</data-path>\n   <template-path>c:/casparcg\</template-path>\n   <initial-path>C:\CasparCG Server 2.3.3/</initial-path>\n</paths>\n\r\n
[2022-05-15 11:33:55.943] [info]    Received message from 127.0.0.1: VERSION\r\n
[2022-05-15 11:33:55.944] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:33:55.944] [info]    Received message from 127.0.0.1: INFO\r\n
[2022-05-15 11:33:55.944] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:33:55.958] [info]    Received message from 127.0.0.1: mixer 1- opacity 1.0\r\n
[2022-05-15 11:33:55.960] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:55.960] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:33:55.960] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:55.962] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:33:55.963] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"592\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:33:55.967] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:55.968] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:33:56.011] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 0\r\n
[2022-05-15 11:33:56.012] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 1\r\n
[2022-05-15 11:33:56.012] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:56.012] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:33:56.400] [info]    Received message from 127.0.0.1: info 1\r\n
[2022-05-15 11:33:56.404] [info]    Sent more than 512 bytes to 127.0.0.1
[2022-05-15 11:35:12.011] [info]    Received message from 127.0.0.1: play 1-1 decklink 1\r\n
[2022-05-15 11:35:12.078] [info]    DeckLink Duo 2 [1|1080i5000] Initialized
[2022-05-15 11:35:12.084] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:35:55.563] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:35:55.603] [info]    DeckLink Duo 2 [2|1080i5000] Initialized
[2022-05-15 11:35:55.605] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:35:55.808] [info]    DeckLink Duo 2 [1|1080i5000] Destroyed.
[2022-05-15 11:39:12.804] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:39:12.849] [error]   Exception: C:\Program Files (x86)\Jenkins\workspace\casparcg-server-dep\master\src\modules\decklink\producer\decklink_producer.cpp(373): Throw in function __cdecl caspar::decklink::decklink_producer::decklink_producer(const struct caspar::core::video_format_desc &,int,const class caspar::spl::shared_ptr<class caspar::core::frame_factory> &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &,bool)
[2022-05-15 11:39:12.849] [error]   Dynamic exception type: class boost::exception_detail::clone_impl<struct caspar::caspar_exception>
[2022-05-15 11:39:12.849] [error]   [struct boost::errinfo_api_function_ * __ptr64] = EnableVideoInput
[2022-05-15 11:39:12.849] [error]   [struct caspar::tag_msg_info * __ptr64] = DeckLink Duo 2 [2|1080i5000] Could not enable video input.
[2022-05-15 11:39:12.849] [error]   [struct caspar::tag_stacktrace_info * __ptr64] =  0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:12.849] [error]    1# 0x00007FF788D23420 in casparcg
[2022-05-15 11:39:12.849] [error]    2# 0x00007FF788F58304 in casparcg
[2022-05-15 11:39:12.849] [error]    3# 0x00007FF788F5C63F in casparcg
[2022-05-15 11:39:12.849] [error]    4# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:12.849] [error]    5# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:12.849] [error]    6# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:12.849] [error]    7# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:12.849] [error]    8# configthreadlocale in ucrtbase
[2022-05-15 11:39:12.849] [error]    9# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:12.849] [error]   10# RtlUserThreadStart in ntdll
[2022-05-15 11:39:12.849] [error]   
[2022-05-15 11:39:12.849] [error]   

[2022-05-15 11:39:12.849] [error]   
[2022-05-15 11:39:12.941] [error]    Turn on log level debug for stacktrace.
[2022-05-15 11:39:12.941] [info]    Sent message to 127.0.0.1:404 PLAY FAILED\r\n
[2022-05-15 11:39:14.883] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:39:14.918] [error]   Exception: C:\Program Files (x86)\Jenkins\workspace\casparcg-server-dep\master\src\modules\decklink\producer\decklink_producer.cpp(373): Throw in function __cdecl caspar::decklink::decklink_producer::decklink_producer(const struct caspar::core::video_format_desc &,int,const class caspar::spl::shared_ptr<class caspar::core::frame_factory> &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &,bool)
[2022-05-15 11:39:14.918] [error]   Dynamic exception type: class boost::exception_detail::clone_impl<struct caspar::caspar_exception>
[2022-05-15 11:39:14.918] [error]   [struct boost::errinfo_api_function_ * __ptr64] = EnableVideoInput
[2022-05-15 11:39:14.918] [error]   [struct caspar::tag_msg_info * __ptr64] = DeckLink Duo 2 [2|1080i5000] Could not enable video input.
[2022-05-15 11:39:14.918] [error]   [struct caspar::tag_stacktrace_info * __ptr64] =  0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:14.918] [error]    1# 0x00007FF788D23420 in casparcg
[2022-05-15 11:39:14.918] [error]    2# 0x00007FF788F58304 in casparcg
[2022-05-15 11:39:14.918] [error]    3# 0x00007FF788F5C63F in casparcg
[2022-05-15 11:39:14.918] [error]    4# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:14.918] [error]    5# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:14.918] [error]    6# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:14.918] [error]    7# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:14.918] [error]    8# configthreadlocale in ucrtbase
[2022-05-15 11:39:14.918] [error]    9# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:14.918] [error]   10# RtlUserThreadStart in ntdll
[2022-05-15 11:39:14.918] [error]   
[2022-05-15 11:39:14.918] [error]   

[2022-05-15 11:39:14.918] [error]    0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:14.918] [error]    1# 0x00007FF788CE9CDF in casparcg
[2022-05-15 11:39:14.918] [error]    2# 0x00007FF789212BFB in casparcg
[2022-05-15 11:39:14.918] [error]    3# 0x00007FFF66CC1030 in VCRUNTIME140
[2022-05-15 11:39:14.918] [error]    4# is_exception_typeof in VCRUNTIME140
[2022-05-15 11:39:14.918] [error]    5# RtlCaptureContext2 in ntdll
[2022-05-15 11:39:14.918] [error]    6# 0x00007FF788DD85B8 in casparcg
[2022-05-15 11:39:14.918] [error]    7# 0x00007FF788DDBE0C in casparcg
[2022-05-15 11:39:14.918] [error]    8# 0x00007FF788DDAEA3 in casparcg
[2022-05-15 11:39:14.918] [error]    9# 0x00007FF788E82B4C in casparcg
[2022-05-15 11:39:14.918] [error]   10# 0x00007FF788E8FC47 in casparcg
[2022-05-15 11:39:14.918] [error]   11# 0x00007FF788E72F1C in casparcg
[2022-05-15 11:39:14.918] [error]   12# 0x00007FF788D12E23 in casparcg
[2022-05-15 11:39:14.918] [error]   13# 0x00007FF788EBB45C in casparcg
[2022-05-15 11:39:14.918] [error]   14# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:14.918] [error]   15# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:14.918] [error]   16# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:14.918] [error]   17# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:14.918] [error]   18# configthreadlocale in ucrtbase
[2022-05-15 11:39:14.918] [error]   19# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:14.918] [error]   20# RtlUserThreadStart in ntdll
[2022-05-15 11:39:14.918] [error]   
[2022-05-15 11:39:15.002] [error]    Turn on log level debug for stacktrace.
[2022-05-15 11:39:15.003] [info]    Sent message to 127.0.0.1:404 PLAY FAILED\r\n
[2022-05-15 11:39:18.530] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:39:18.566] [error]   Exception: C:\Program Files (x86)\Jenkins\workspace\casparcg-server-dep\master\src\modules\decklink\producer\decklink_producer.cpp(373): Throw in function __cdecl caspar::decklink::decklink_producer::decklink_producer(const struct caspar::core::video_format_desc &,int,const class caspar::spl::shared_ptr<class caspar::core::frame_factory> &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &,bool)
[2022-05-15 11:39:18.566] [error]   Dynamic exception type: class boost::exception_detail::clone_impl<struct caspar::caspar_exception>
[2022-05-15 11:39:18.566] [error]   [struct boost::errinfo_api_function_ * __ptr64] = EnableVideoInput
[2022-05-15 11:39:18.566] [error]   [struct caspar::tag_msg_info * __ptr64] = DeckLink Duo 2 [2|1080i5000] Could not enable video input.
[2022-05-15 11:39:18.566] [error]   [struct caspar::tag_stacktrace_info * __ptr64] =  0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:18.566] [error]    1# 0x00007FF788D23420 in casparcg
[2022-05-15 11:39:18.566] [error]    2# 0x00007FF788F58304 in casparcg
[2022-05-15 11:39:18.566] [error]    3# 0x00007FF788F5C63F in casparcg
[2022-05-15 11:39:18.566] [error]    4# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:18.566] [error]    5# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:18.566] [error]    6# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:18.566] [error]    7# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:18.566] [error]    8# configthreadlocale in ucrtbase
[2022-05-15 11:39:18.566] [error]    9# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:18.566] [error]   10# RtlUserThreadStart in ntdll
[2022-05-15 11:39:18.566] [error]   
[2022-05-15 11:39:18.566] [error]   

[2022-05-15 11:39:18.566] [error]    0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:18.566] [error]    1# 0x00007FF788CE9CDF in casparcg
[2022-05-15 11:39:18.566] [error]    2# 0x00007FF789212BFB in casparcg
[2022-05-15 11:39:18.566] [error]    3# 0x00007FFF66CC1030 in VCRUNTIME140
[2022-05-15 11:39:18.566] [error]    4# is_exception_typeof in VCRUNTIME140
[2022-05-15 11:39:18.566] [error]    5# RtlCaptureContext2 in ntdll
[2022-05-15 11:39:18.566] [error]    6# 0x00007FF788DD85B8 in casparcg
[2022-05-15 11:39:18.566] [error]    7# 0x00007FF788DDBE0C in casparcg
[2022-05-15 11:39:18.566] [error]    8# 0x00007FF788DDAEA3 in casparcg
[2022-05-15 11:39:18.566] [error]    9# 0x00007FF788E82B4C in casparcg
[2022-05-15 11:39:18.566] [error]   10# 0x00007FF788E8FC47 in casparcg
[2022-05-15 11:39:18.566] [error]   11# 0x00007FF788E72F1C in casparcg
[2022-05-15 11:39:18.566] [error]   12# 0x00007FF788D12E23 in casparcg
[2022-05-15 11:39:18.566] [error]   13# 0x00007FF788EBB45C in casparcg
[2022-05-15 11:39:18.566] [error]   14# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:18.566] [error]   15# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:18.566] [error]   16# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:18.566] [error]   17# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:18.566] [error]   18# configthreadlocale in ucrtbase
[2022-05-15 11:39:18.566] [error]   19# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:18.566] [error]   20# RtlUserThreadStart in ntdll
[2022-05-15 11:39:18.566] [error]   
[2022-05-15 11:39:18.653] [error]    Turn on log level debug for stacktrace.
[2022-05-15 11:39:18.653] [info]    Sent message to 127.0.0.1:404 PLAY FAILED\r\n
[2022-05-15 11:39:19.404] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:39:19.439] [error]   Exception: C:\Program Files (x86)\Jenkins\workspace\casparcg-server-dep\master\src\modules\decklink\producer\decklink_producer.cpp(373): Throw in function __cdecl caspar::decklink::decklink_producer::decklink_producer(const struct caspar::core::video_format_desc &,int,const class caspar::spl::shared_ptr<class caspar::core::frame_factory> &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &,bool)
[2022-05-15 11:39:19.439] [error]   Dynamic exception type: class boost::exception_detail::clone_impl<struct caspar::caspar_exception>
[2022-05-15 11:39:19.439] [error]   [struct boost::errinfo_api_function_ * __ptr64] = EnableVideoInput
[2022-05-15 11:39:19.439] [error]   [struct caspar::tag_msg_info * __ptr64] = DeckLink Duo 2 [2|1080i5000] Could not enable video input.
[2022-05-15 11:39:19.439] [error]   [struct caspar::tag_stacktrace_info * __ptr64] =  0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:19.439] [error]    1# 0x00007FF788D23420 in casparcg
[2022-05-15 11:39:19.439] [error]    2# 0x00007FF788F58304 in casparcg
[2022-05-15 11:39:19.439] [error]    3# 0x00007FF788F5C63F in casparcg
[2022-05-15 11:39:19.439] [error]    4# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:19.439] [error]    5# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:19.439] [error]    6# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:19.439] [error]    7# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:19.439] [error]    8# configthreadlocale in ucrtbase
[2022-05-15 11:39:19.439] [error]    9# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:19.439] [error]   10# RtlUserThreadStart in ntdll
[2022-05-15 11:39:19.439] [error]   
[2022-05-15 11:39:19.439] [error]   

[2022-05-15 11:39:19.439] [error]    0# 0x00007FF788CEA3AE in casparcg
[2022-05-15 11:39:19.439] [error]    1# 0x00007FF788CE9CDF in casparcg
[2022-05-15 11:39:19.439] [error]    2# 0x00007FF789212BFB in casparcg
[2022-05-15 11:39:19.439] [error]    3# 0x00007FFF66CC1030 in VCRUNTIME140
[2022-05-15 11:39:19.439] [error]    4# is_exception_typeof in VCRUNTIME140
[2022-05-15 11:39:19.439] [error]    5# RtlCaptureContext2 in ntdll
[2022-05-15 11:39:19.439] [error]    6# 0x00007FF788DD85B8 in casparcg
[2022-05-15 11:39:19.439] [error]    7# 0x00007FF788DDBE0C in casparcg
[2022-05-15 11:39:19.439] [error]    8# 0x00007FF788DDAEA3 in casparcg
[2022-05-15 11:39:19.439] [error]    9# 0x00007FF788E82B4C in casparcg
[2022-05-15 11:39:19.439] [error]   10# 0x00007FF788E8FC47 in casparcg
[2022-05-15 11:39:19.439] [error]   11# 0x00007FF788E72F1C in casparcg
[2022-05-15 11:39:19.439] [error]   12# 0x00007FF788D12E23 in casparcg
[2022-05-15 11:39:19.439] [error]   13# 0x00007FF788EBB45C in casparcg
[2022-05-15 11:39:19.439] [error]   14# 0x00007FF788D3ADA8 in casparcg
[2022-05-15 11:39:19.439] [error]   15# 0x00007FF788DDD432 in casparcg
[2022-05-15 11:39:19.439] [error]   16# 0x00007FF788DD9DC0 in casparcg
[2022-05-15 11:39:19.439] [error]   17# 0x00007FF788CE50E9 in casparcg
[2022-05-15 11:39:19.439] [error]   18# configthreadlocale in ucrtbase
[2022-05-15 11:39:19.439] [error]   19# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:39:19.439] [error]   20# RtlUserThreadStart in ntdll
[2022-05-15 11:39:19.439] [error]   
[2022-05-15 11:39:19.514] [error]    Turn on log level debug for stacktrace.
[2022-05-15 11:39:19.515] [info]    Sent message to 127.0.0.1:404 PLAY FAILED\r\n
[2022-05-15 11:42:59.558] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515114259.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:42:59.559] [info]    ffmpeg[ch1/20220515114259.mp4] Initialized.
[2022-05-15 11:42:59.559] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:42:59.576] [info]    [ffmpeg] [libx264 @ 000001104B01B740] using SAR=1/1
[2022-05-15 11:42:59.576] [info]    
[2022-05-15 11:42:59.579] [info]    [ffmpeg] [libx264 @ 000001104B01B740] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:42:59.579] [info]    
[2022-05-15 11:42:59.586] [info]    [ffmpeg] [libx264 @ 000001104B01B740] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:42:59.586] [info]    
[2022-05-15 11:42:59.590] [info]    [ffmpeg] [Parsed_pan_0 @ 000001104AF69340] Pure channel mapping detected:
[2022-05-15 11:42:59.590] [info]    [ffmpeg]  0
[2022-05-15 11:42:59.591] [info]    [ffmpeg]  1
[2022-05-15 11:42:59.591] [info]    [ffmpeg] 
[2022-05-15 11:42:59.591] [info]    
[2022-05-15 11:42:59.597] [warning] ffmpeg[ch1/20220515114259.mp4] Unused option s=1920:1080
[2022-05-15 11:43:01.005] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515114301.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:43:01.005] [info]    ffmpeg[ch2/20220515114301.mp4] Initialized.
[2022-05-15 11:43:01.005] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:43:01.010] [info]    [ffmpeg] [libx264 @ 0000011097C7B980] using SAR=1/1
[2022-05-15 11:43:01.010] [info]    
[2022-05-15 11:43:01.010] [info]    [ffmpeg] [libx264 @ 0000011097C7B980] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:43:01.010] [info]    
[2022-05-15 11:43:01.016] [info]    [ffmpeg] [libx264 @ 0000011097C7B980] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:43:01.016] [info]    
[2022-05-15 11:43:01.022] [info]    [ffmpeg] [Parsed_pan_0 @ 000001104AF6A940] Pure channel mapping detected:
[2022-05-15 11:43:01.022] [info]    [ffmpeg]  0
[2022-05-15 11:43:01.022] [info]    [ffmpeg]  1
[2022-05-15 11:43:01.022] [info]    [ffmpeg] 
[2022-05-15 11:43:01.022] [info]    
[2022-05-15 11:43:01.024] [warning] ffmpeg[ch2/20220515114301.mp4] Unused option s=1920:1080
[2022-05-15 11:43:03.154] [info]    Received message from 127.0.0.1: play 2-1 decklink 4\r\n
[2022-05-15 11:43:03.208] [info]    DeckLink Duo 2 [4|1080i5000] Initialized
[2022-05-15 11:43:03.210] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:43:03.463] [warning] DeckLink Duo 2 [4|1080i5000] in-sync changed: -0.0111042
[2022-05-15 11:43:03.465] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 0.02
[2022-05-15 11:43:03.505] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 0.04
[2022-05-15 11:43:03.544] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: -0.0104375
[2022-05-15 11:44:42.953] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (1 connections).
[2022-05-15 11:44:42.954] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (0 connections).
[2022-05-15 11:45:02.576] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (1 connections).
[2022-05-15 11:45:02.578] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (2 connections).
[2022-05-15 11:45:02.582] [info]    Received message from 127.0.0.1: VERSION SERVER\r\n
[2022-05-15 11:45:02.582] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:45:02.583] [info]    Received message from 127.0.0.1: VERSION FLASH\r\n
[2022-05-15 11:45:02.584] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:45:02.588] [info]    Received message from 127.0.0.1: VERSION TEMPLATEHOST\r\n
[2022-05-15 11:45:02.588] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:45:02.589] [info]    Received message from 127.0.0.1: info\r\n
[2022-05-15 11:45:02.589] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:45:02.593] [info]    Received message from 127.0.0.1: info paths\r\n
[2022-05-15 11:45:02.593] [info]    Sent message to 127.0.0.1:201 INFO PATHS OK\r\n<?xml version="1.0" encoding="utf-8"?>\n<paths>\n   <media-path>d:/casparcg/_media\</media-path>\n   <log-path>log\</log-path>\n   <data-path>data\</data-path>\n   <template-path>c:/casparcg\</template-path>\n   <initial-path>C:\CasparCG Server 2.3.3/</initial-path>\n</paths>\n\r\n
[2022-05-15 11:45:02.933] [info]    Received message from 127.0.0.1: VERSION\r\n
[2022-05-15 11:45:02.933] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:45:02.934] [info]    Received message from 127.0.0.1: INFO\r\n
[2022-05-15 11:45:02.934] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:45:02.966] [info]    Received message from 127.0.0.1: mixer 1- opacity 1.0\r\n
[2022-05-15 11:45:02.966] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:02.968] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:45:02.968] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:02.969] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"592\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:45:02.969] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:02.970] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:45:03.019] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 0\r\n
[2022-05-15 11:45:03.019] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 1\r\n
[2022-05-15 11:45:03.019] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:03.019] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:45:03.348] [info]    Received message from 127.0.0.1: info 1\r\n
[2022-05-15 11:45:03.349] [info]    Sent more than 512 bytes to 127.0.0.1
[2022-05-15 11:45:48.904] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (1 connections).
[2022-05-15 11:45:48.905] [info]    async_event_server[:5250] Client 127.0.0.1 disconnected (0 connections).
[2022-05-15 11:49:28.885] [info]    ############################################################################
[2022-05-15 11:49:28.886] [info]    CasparCG Server is distributed by the Swedish Broadcasting Corporation (SVT)
[2022-05-15 11:49:28.886] [info]    under the GNU General Public License GPLv3 or higher.
[2022-05-15 11:49:28.886] [info]    Please see LICENSE.TXT for details.
[2022-05-15 11:49:28.886] [info]    http://www.casparcg.com/
[2022-05-15 11:49:28.886] [info]    ############################################################################
[2022-05-15 11:49:28.886] [info]    Starting CasparCG Video and Graphics Playout Server 2.3.3 d6f06dab Dev
[2022-05-15 11:49:29.137] [info]    Initializing OpenGL Device.
[2022-05-15 11:49:29.143] [info]    Initialized OpenGL 4.5.0 NVIDIA 472.08 NVIDIA Corporation
[2022-05-15 11:49:29.144] [info]    Initialized image module.
[2022-05-15 11:49:29.145] [info]    Initialized ffmpeg module.
[2022-05-15 11:49:29.145] [info]    Initialized oal module.
[2022-05-15 11:49:29.145] [info]    Initialized decklink module.
[2022-05-15 11:49:29.145] [info]    Initialized screen module.
[2022-05-15 11:49:29.145] [info]    Initialized newtek module.
[2022-05-15 11:49:29.430] [info]    Initialized html module.
[2022-05-15 11:49:29.430] [info]    Flash support is disabled
[2022-05-15 11:49:29.430] [info]    Initialized flash module.
[2022-05-15 11:49:29.432] [info]    Initialized bluefish module.
[2022-05-15 11:49:29.432] [info]    "C:/CasparCG Server 2.3.3\casparcg.config":
[2022-05-15 11:49:29.432] [info]    -----------------------------------------
[2022-05-15 11:49:29.432] [info]    <?xml version="1.0" encoding="utf-8"?>
[2022-05-15 11:49:29.432] [info]    <configuration>
[2022-05-15 11:49:29.432] [info]       <paths>
[2022-05-15 11:49:29.432] [info]          <media-path>d:/casparcg/_media\</media-path>
[2022-05-15 11:49:29.432] [info]          <log-path>log\</log-path>
[2022-05-15 11:49:29.432] [info]          <data-path>data\</data-path>
[2022-05-15 11:49:29.432] [info]          <template-path>c:/casparcg\</template-path>
[2022-05-15 11:49:29.432] [info]          <thumbnails-path>thumbnails\</thumbnails-path>
[2022-05-15 11:49:29.432] [info]       </paths>
[2022-05-15 11:49:29.432] [info]       <channels>
[2022-05-15 11:49:29.432] [info]          <channel>
[2022-05-15 11:49:29.432] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:49:29.432] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:49:29.432] [info]             <consumers>
[2022-05-15 11:49:29.432] [info]                <screen>
[2022-05-15 11:49:29.432] [info]                   <device>1</device>
[2022-05-15 11:49:29.432] [info]                </screen>
[2022-05-15 11:49:29.432] [info]                <system-audio/>
[2022-05-15 11:49:29.432] [info]             </consumers>
[2022-05-15 11:49:29.432] [info]          </channel>
[2022-05-15 11:49:29.432] [info]          <channel>
[2022-05-15 11:49:29.432] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:49:29.432] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:49:29.432] [info]             <consumers>
[2022-05-15 11:49:29.432] [info]                <screen>
[2022-05-15 11:49:29.432] [info]                   <device>1</device>
[2022-05-15 11:49:29.432] [info]                </screen>
[2022-05-15 11:49:29.432] [info]                <system-audio/>
[2022-05-15 11:49:29.432] [info]             </consumers>
[2022-05-15 11:49:29.432] [info]          </channel>
[2022-05-15 11:49:29.432] [info]          <channel>
[2022-05-15 11:49:29.432] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:49:29.432] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:49:29.432] [info]             <consumers>
[2022-05-15 11:49:29.432] [info]                <screen>
[2022-05-15 11:49:29.432] [info]                   <device>1</device>
[2022-05-15 11:49:29.432] [info]                </screen>
[2022-05-15 11:49:29.432] [info]                <system-audio/>
[2022-05-15 11:49:29.432] [info]             </consumers>
[2022-05-15 11:49:29.432] [info]          </channel>
[2022-05-15 11:49:29.432] [info]          <channel>
[2022-05-15 11:49:29.432] [info]             <video-mode>1080i5000</video-mode>
[2022-05-15 11:49:29.432] [info]             <channel-layout>stereo</channel-layout>
[2022-05-15 11:49:29.432] [info]             <consumers>
[2022-05-15 11:49:29.432] [info]                <screen>
[2022-05-15 11:49:29.432] [info]                   <device>1</device>
[2022-05-15 11:49:29.432] [info]                </screen>
[2022-05-15 11:49:29.432] [info]                <system-audio/>
[2022-05-15 11:49:29.432] [info]             </consumers>
[2022-05-15 11:49:29.432] [info]          </channel>
[2022-05-15 11:49:29.432] [info]       </channels>
[2022-05-15 11:49:29.432] [info]       <controllers>
[2022-05-15 11:49:29.432] [info]          <tcp>
[2022-05-15 11:49:29.432] [info]             <port>5250</port>
[2022-05-15 11:49:29.432] [info]             <protocol>AMCP</protocol>
[2022-05-15 11:49:29.432] [info]          </tcp>
[2022-05-15 11:49:29.432] [info]       </controllers>
[2022-05-15 11:49:29.432] [info]       <osc>
[2022-05-15 11:49:29.432] [info]          <default-port>6250</default-port>
[2022-05-15 11:49:29.432] [info]          <predefined-clients>
[2022-05-15 11:49:29.432] [info]             <predefined-client>
[2022-05-15 11:49:29.432] [info]                <address>127.0.0.1</address>
[2022-05-15 11:49:29.432] [info]                <port>6251</port>
[2022-05-15 11:49:29.432] [info]             </predefined-client>
[2022-05-15 11:49:29.432] [info]             <predefined-client>
[2022-05-15 11:49:29.432] [info]                <address>127.0.0.1</address>
[2022-05-15 11:49:29.432] [info]                <port>6252</port>
[2022-05-15 11:49:29.432] [info]             </predefined-client>
[2022-05-15 11:49:29.432] [info]             <predefined-client>
[2022-05-15 11:49:29.432] [info]                <address>127.0.0.1</address>
[2022-05-15 11:49:29.432] [info]                <port>6253</port>
[2022-05-15 11:49:29.432] [info]             </predefined-client>
[2022-05-15 11:49:29.432] [info]             <predefined-client>
[2022-05-15 11:49:29.432] [info]                <address>127.0.0.1</address>
[2022-05-15 11:49:29.432] [info]                <port>6254</port>
[2022-05-15 11:49:29.432] [info]             </predefined-client>
[2022-05-15 11:49:29.432] [info]          </predefined-clients>
[2022-05-15 11:49:29.432] [info]       </osc>
[2022-05-15 11:49:29.432] [info]    </configuration>
[2022-05-15 11:49:29.432] [info]    -----------------------------------------
[2022-05-15 11:49:29.436] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 1
[2022-05-15 11:49:29.437] [info]    video_channel[1|1080i5000] Successfully Initialized.
[2022-05-15 11:49:29.438] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 2
[2022-05-15 11:49:29.438] [info]    video_channel[2|1080i5000] Successfully Initialized.
[2022-05-15 11:49:29.438] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 3
[2022-05-15 11:49:29.439] [info]    video_channel[3|1080i5000] Successfully Initialized.
[2022-05-15 11:49:29.439] [info]    Initialized OpenGL Accelerated GPU Image Mixer for channel 4
[2022-05-15 11:49:29.440] [info]    video_channel[4|1080i5000] Successfully Initialized.
[2022-05-15 11:49:29.442] [info]    Screen consumer [1|1080i5000] Initialized.
[2022-05-15 11:49:29.474] [info]    oal[1|1080i5000] Initialized.
[2022-05-15 11:49:29.475] [info]    Screen consumer [2|1080i5000] Initialized.
[2022-05-15 11:49:29.476] [info]    oal[2|1080i5000] Initialized.
[2022-05-15 11:49:29.477] [info]    Screen consumer [3|1080i5000] Initialized.
[2022-05-15 11:49:29.478] [info]    oal[3|1080i5000] Initialized.
[2022-05-15 11:49:29.614] [info]    Screen consumer [4|1080i5000] Initialized.
[2022-05-15 11:49:29.614] [info]    oal[4|1080i5000] Initialized.
[2022-05-15 11:49:29.614] [info]    Initialized channels.
[2022-05-15 11:49:29.614] [info]    Initialized command repository.
[2022-05-15 11:49:29.614] [info]    Initialized startup producers.
[2022-05-15 11:49:29.616] [info]    Initialized controllers.
[2022-05-15 11:49:29.616] [info]    Initialized osc.
[2022-05-15 11:49:49.175] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (1 connections).
[2022-05-15 11:49:49.176] [info]    async_event_server[:5250] Accepted connection from 127.0.0.1 (2 connections).
[2022-05-15 11:49:49.178] [info]    Received message from 127.0.0.1: VERSION SERVER\r\n
[2022-05-15 11:49:49.180] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:49:49.182] [info]    Received message from 127.0.0.1: VERSION FLASH\r\n
[2022-05-15 11:49:49.182] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:49:49.183] [info]    Received message from 127.0.0.1: VERSION TEMPLATEHOST\r\n
[2022-05-15 11:49:49.183] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:49:49.184] [info]    Received message from 127.0.0.1: info\r\n
[2022-05-15 11:49:49.185] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:49:49.187] [info]    Received message from 127.0.0.1: info paths\r\n
[2022-05-15 11:49:49.188] [info]    Sent message to 127.0.0.1:201 INFO PATHS OK\r\n<?xml version="1.0" encoding="utf-8"?>\n<paths>\n   <media-path>d:/casparcg/_media\</media-path>\n   <log-path>log\</log-path>\n   <data-path>data\</data-path>\n   <template-path>c:/casparcg\</template-path>\n   <initial-path>C:\CasparCG Server 2.3.3/</initial-path>\n</paths>\n\r\n
[2022-05-15 11:49:49.622] [info]    Received message from 127.0.0.1: VERSION\r\n
[2022-05-15 11:49:49.623] [info]    Sent message to 127.0.0.1:201 VERSION OK\r\n2.3.3 d6f06dab Dev\r\n
[2022-05-15 11:49:49.626] [info]    Received message from 127.0.0.1: INFO\r\n
[2022-05-15 11:49:49.626] [info]    Sent message to 127.0.0.1:200 INFO OK\r\n1 1080i5000 PLAYING\r\n2 1080i5000 PLAYING\r\n3 1080i5000 PLAYING\r\n4 1080i5000 PLAYING\r\n\r\n
[2022-05-15 11:49:49.650] [info]    Received message from 127.0.0.1: mixer 1- opacity 1.0\r\n
[2022-05-15 11:49:49.651] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:49:49.652] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.652] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.652] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"0\" /></componentData></templateData>"\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"0\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: mixer 1-41 opacity 1.0\r\n
[2022-05-15 11:49:49.653] [info]    Received message from 127.0.0.1: CG 1-41 UPDATE 41  "<templateData><componentData id=\"speed\"><data id=\"text\" value=\"2\" /></componentData><componentData id=\"logowidth\"><data id=\"text\" value=\"160\" /></componentData><componentData id=\"logoheight\"><data id=\"text\" value=\"120\" /></componentData><componentData id=\"logox\"><data id=\"text\" value=\"592\" /></componentData><componentData id=\"logoy\"><data id=\"text\" value=\"6\" /></componentData></templateData>"\r\n
[2022-05-15 11:49:49.657] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:49:49.657] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.657] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:49:49.658] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.658] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:49:49.658] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.658] [info]    Sent message to 127.0.0.1:403 CG UPDATE FAILED\r\n
[2022-05-15 11:49:49.704] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 0\r\n
[2022-05-15 11:49:49.704] [info]    Received message from 127.0.0.1: mixer 1- fill 0 0 1 1\r\n
[2022-05-15 11:49:49.704] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:49.704] [info]    Sent message to 127.0.0.1:202 MIXER OK\r\n
[2022-05-15 11:49:50.134] [info]    Received message from 127.0.0.1: info 1\r\n
[2022-05-15 11:49:50.138] [info]    Sent more than 512 bytes to 127.0.0.1
[2022-05-15 11:50:10.645] [info]    Received message from 127.0.0.1: play 1-1 decklink 1\r\n
[2022-05-15 11:50:10.763] [info]    DeckLink Duo 2 [1|1080i5000] Initialized
[2022-05-15 11:50:10.769] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:50:27.637] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:50:27.695] [info]    DeckLink Duo 2 [2|1080i5000] Initialized
[2022-05-15 11:50:27.696] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:50:27.910] [info]    DeckLink Duo 2 [1|1080i5000] Destroyed.
[2022-05-15 11:50:38.275] [info]    Received message from 127.0.0.1: play 1-1 decklink 2\r\n
[2022-05-15 11:50:38.392] [error]   Exception: C:\Program Files (x86)\Jenkins\workspace\casparcg-server-dep\master\src\modules\decklink\producer\decklink_producer.cpp(373): Throw in function __cdecl caspar::decklink::decklink_producer::decklink_producer(const struct caspar::core::video_format_desc &,int,const class caspar::spl::shared_ptr<class caspar::core::frame_factory> &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,const class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &,bool)
[2022-05-15 11:50:38.392] [error]   Dynamic exception type: class boost::exception_detail::clone_impl<struct caspar::caspar_exception>
[2022-05-15 11:50:38.392] [error]   [struct boost::errinfo_api_function_ * __ptr64] = EnableVideoInput
[2022-05-15 11:50:38.392] [error]   [struct caspar::tag_msg_info * __ptr64] = DeckLink Duo 2 [2|1080i5000] Could not enable video input.
[2022-05-15 11:50:38.392] [error]   [struct caspar::tag_stacktrace_info * __ptr64] =  0# 0x00007FF72BB3A3AE in casparcg
[2022-05-15 11:50:38.392] [error]    1# 0x00007FF72BB73420 in casparcg
[2022-05-15 11:50:38.392] [error]    2# 0x00007FF72BDA8304 in casparcg
[2022-05-15 11:50:38.392] [error]    3# 0x00007FF72BDAC63F in casparcg
[2022-05-15 11:50:38.392] [error]    4# 0x00007FF72BB8ADA8 in casparcg
[2022-05-15 11:50:38.392] [error]    5# 0x00007FF72BC2D432 in casparcg
[2022-05-15 11:50:38.392] [error]    6# 0x00007FF72BC29DC0 in casparcg
[2022-05-15 11:50:38.392] [error]    7# 0x00007FF72BB350E9 in casparcg
[2022-05-15 11:50:38.392] [error]    8# configthreadlocale in ucrtbase
[2022-05-15 11:50:38.392] [error]    9# BaseThreadInitThunk in KERNEL32
[2022-05-15 11:50:38.392] [error]   10# RtlUserThreadStart in ntdll
[2022-05-15 11:50:38.392] [error]   
[2022-05-15 11:50:38.392] [error]   

[2022-05-15 11:50:38.392] [error]   
[2022-05-15 11:50:38.496] [error]    Turn on log level debug for stacktrace.
[2022-05-15 11:50:38.496] [info]    Sent message to 127.0.0.1:404 PLAY FAILED\r\n
[2022-05-15 11:51:51.133] [info]    Received message from 127.0.0.1: play 2-1 decklink 4\r\n
[2022-05-15 11:51:51.258] [info]    DeckLink Duo 2 [4|1080i5000] Initialized
[2022-05-15 11:51:51.259] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 11:51:51.482] [warning] DeckLink Duo 2 [4|1080i5000] in-sync changed: 0.0190208
[2022-05-15 11:51:51.485] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 0.02
[2022-05-15 11:51:51.523] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 0.04
[2022-05-15 11:51:51.564] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 0.0195208
[2022-05-15 11:52:48.979] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515115248.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:52:48.981] [info]    ffmpeg[ch1/20220515115248.mp4] Initialized.
[2022-05-15 11:52:48.981] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:52:49.002] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] using SAR=1/1
[2022-05-15 11:52:49.002] [info]    
[2022-05-15 11:52:49.006] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:52:49.006] [info]    
[2022-05-15 11:52:49.013] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:52:49.013] [info]    
[2022-05-15 11:52:49.025] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017B5568FA00] Pure channel mapping detected:
[2022-05-15 11:52:49.025] [info]    [ffmpeg]  0
[2022-05-15 11:52:49.025] [info]    [ffmpeg]  1
[2022-05-15 11:52:49.025] [info]    [ffmpeg] 
[2022-05-15 11:52:49.025] [info]    
[2022-05-15 11:52:49.031] [warning] ffmpeg[ch1/20220515115248.mp4] Unused option s=1920:1080
[2022-05-15 11:52:49.985] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515115249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 11:52:49.986] [info]    ffmpeg[ch2/20220515115249.mp4] Initialized.
[2022-05-15 11:52:49.986] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 11:52:49.995] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] using SAR=1/1
[2022-05-15 11:52:49.995] [info]    
[2022-05-15 11:52:49.996] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 11:52:49.996] [info]    
[2022-05-15 11:52:50.003] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 11:52:50.003] [info]    
[2022-05-15 11:52:50.017] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7200] Pure channel mapping detected:
[2022-05-15 11:52:50.017] [info]    [ffmpeg]  0
[2022-05-15 11:52:50.017] [info]    [ffmpeg]  1
[2022-05-15 11:52:50.017] [info]    [ffmpeg] 
[2022-05-15 11:52:50.017] [info]    
[2022-05-15 11:52:50.018] [warning] ffmpeg[ch2/20220515115249.mp4] Unused option s=1920:1080
[2022-05-15 12:22:48.995] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515115248.mp4\r\n
[2022-05-15 12:22:48.996] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 12:22:48.996] [info]    ffmpeg[ch1/20220515115248.mp4] Uninitialized.
[2022-05-15 12:22:48.997] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515122248.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 12:22:48.998] [info]    ffmpeg[ch1/20220515122248.mp4] Initialized.
[2022-05-15 12:22:48.998] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 12:22:49.011] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] using SAR=1/1
[2022-05-15 12:22:49.011] [info]    
[2022-05-15 12:22:49.012] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 12:22:49.012] [info]    
[2022-05-15 12:22:49.018] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 12:22:49.018] [info]    
[2022-05-15 12:22:49.026] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7900] Pure channel mapping detected:
[2022-05-15 12:22:49.026] [info]    [ffmpeg]  0
[2022-05-15 12:22:49.027] [info]    [ffmpeg]  1
[2022-05-15 12:22:49.027] [info]    [ffmpeg] 
[2022-05-15 12:22:49.027] [info]    
[2022-05-15 12:22:49.028] [warning] ffmpeg[ch1/20220515122248.mp4] Unused option s=1920:1080
[2022-05-15 12:22:49.079] [info]    [ffmpeg] [aac @ 0000017B1CDD4200] Qavg: 11945.667
[2022-05-15 12:22:49.079] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] frame I:361   Avg QP:26.06  size:109523
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] frame P:22816 Avg QP:15.86  size: 68413
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] frame B:66824 Avg QP:21.47  size:  9826
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] consecutive B-frames:  0.8%  0.7%  0.1% 98.4%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] mb I  I16..4: 46.9% 15.4% 37.7%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] mb P  I16..4:  2.4%  1.2%  1.3%  P16..4: 25.9%  6.2%  6.2%  0.0%  0.0%    skip:56.8%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  5.3%  2.3%  0.6%  direct: 5.1%  skip:86.3%  L0:38.0% L1:41.0% BI:20.9%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] 8x8 transform intra:23.8% inter:22.0%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] coded y,uvDC,uvAC intra: 57.6% 61.9% 45.6% inter: 9.5% 6.5% 2.3%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] i16 v,h,dc,p: 52% 34%  7%  8%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.091] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 24% 23%  5%  5%  5%  5%  6%  5%
[2022-05-15 12:22:49.091] [info]    
[2022-05-15 12:22:49.092] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 29% 29% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 12:22:49.092] [info]    
[2022-05-15 12:22:49.092] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] i8c dc,h,v,p: 37% 30% 27%  6%
[2022-05-15 12:22:49.092] [info]    
[2022-05-15 12:22:49.092] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 12:22:49.092] [info]    
[2022-05-15 12:22:49.092] [info]    [ffmpeg] [libx264 @ 0000017B76F898C0] kb/s:10031.29
[2022-05-15 12:22:49.092] [info]    
[2022-05-15 12:22:49.244] [info]    ffmpeg[ch1/20220515115248.mp4] Uninitialized.
[2022-05-15 12:22:49.991] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515115249.mp4\r\n
[2022-05-15 12:22:49.992] [info]    ffmpeg[ch2/20220515115249.mp4] Uninitialized.
[2022-05-15 12:22:49.992] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 12:22:49.995] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515122249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 12:22:49.995] [info]    ffmpeg[ch2/20220515122249.mp4] Initialized.
[2022-05-15 12:22:49.995] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 12:22:50.010] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] using SAR=1/1
[2022-05-15 12:22:50.010] [info]    
[2022-05-15 12:22:50.010] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 12:22:50.010] [info]    
[2022-05-15 12:22:50.021] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 12:22:50.021] [info]    
[2022-05-15 12:22:50.028] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9D00] Pure channel mapping detected:
[2022-05-15 12:22:50.028] [info]    [ffmpeg]  0
[2022-05-15 12:22:50.028] [info]    [ffmpeg]  1
[2022-05-15 12:22:50.028] [info]    [ffmpeg] 
[2022-05-15 12:22:50.028] [info]    
[2022-05-15 12:22:50.031] [warning] ffmpeg[ch2/20220515122249.mp4] Unused option s=1920:1080
[2022-05-15 12:22:50.124] [info]    [ffmpeg] [aac @ 0000017BACA9C2C0] Qavg: 361.656
[2022-05-15 12:22:50.124] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] frame I:490   Avg QP:23.32  size: 98380
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] frame P:24018 Avg QP:19.64  size: 59609
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] frame B:65493 Avg QP:23.16  size:  9433
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] consecutive B-frames:  1.5%  3.7%  2.0% 92.8%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] mb I  I16..4: 25.7% 46.0% 28.3%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] mb P  I16..4:  8.7% 12.8%  2.4%  P16..4: 33.8% 13.0%  8.1%  0.0%  0.0%    skip:21.2%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] mb B  I16..4:  1.3%  1.2%  0.1%  B16..8: 13.5%  3.7%  0.3%  direct: 9.2%  skip:70.7%  L0:43.3% L1:43.0% BI:13.7%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] 8x8 transform intra:51.7% inter:30.9%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] coded y,uvDC,uvAC intra: 53.1% 56.2% 21.7% inter: 11.2% 12.4% 0.7%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] i16 v,h,dc,p: 39% 32% 20%  9%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 27% 24%  4%  4%  5%  5%  4%  5%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 26% 13%  5%  7%  7%  6%  5%  5%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] i8c dc,h,v,p: 46% 28% 20%  6%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] Weighted P-Frames: Y:1.9% UV:0.6%
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.135] [info]    [ffmpeg] [libx264 @ 0000017BACD79AC0] kb/s:9322.96
[2022-05-15 12:22:50.135] [info]    
[2022-05-15 12:22:50.297] [info]    ffmpeg[ch2/20220515115249.mp4] Uninitialized.
[2022-05-15 12:52:48.994] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515122248.mp4\r\n
[2022-05-15 12:52:48.995] [info]    ffmpeg[ch1/20220515122248.mp4] Uninitialized.
[2022-05-15 12:52:48.995] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 12:52:48.997] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515125248.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 12:52:48.998] [info]    ffmpeg[ch1/20220515125248.mp4] Initialized.
[2022-05-15 12:52:48.998] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 12:52:49.016] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] using SAR=1/1
[2022-05-15 12:52:49.016] [info]    
[2022-05-15 12:52:49.017] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 12:52:49.017] [info]    
[2022-05-15 12:52:49.038] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 12:52:49.038] [info]    
[2022-05-15 12:52:49.056] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9B00] Pure channel mapping detected:
[2022-05-15 12:52:49.056] [info]    [ffmpeg]  0
[2022-05-15 12:52:49.056] [info]    [ffmpeg]  1
[2022-05-15 12:52:49.056] [info]    [ffmpeg] 
[2022-05-15 12:52:49.056] [info]    
[2022-05-15 12:52:49.058] [warning] ffmpeg[ch1/20220515125248.mp4] Unused option s=1920:1080
[2022-05-15 12:52:49.072] [info]    [ffmpeg] [aac @ 0000017BF5D8E5C0] Qavg: 6960.500
[2022-05-15 12:52:49.072] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] frame I:360   Avg QP:27.90  size:112942
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] frame P:22754 Avg QP:15.70  size: 68653
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] frame B:66886 Avg QP:21.34  size:  9692
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] consecutive B-frames:  0.7%  0.4%  0.2% 98.6%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] mb I  I16..4: 42.7% 17.1% 40.2%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] mb P  I16..4:  2.5%  1.3%  1.6%  P16..4: 28.5%  6.2%  6.2%  0.0%  0.0%    skip:53.7%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] mb B  I16..4:  0.3%  0.2%  0.1%  B16..8:  5.5%  2.3%  0.6%  direct: 4.9%  skip:86.1%  L0:30.9% L1:49.6% BI:19.4%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] 8x8 transform intra:24.6% inter:22.4%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] coded y,uvDC,uvAC intra: 56.6% 61.7% 41.8% inter: 9.5% 7.4% 2.5%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] i16 v,h,dc,p: 51% 35%  6%  8%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 21% 21%  5%  5%  6%  6%  7%  6%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] i8c dc,h,v,p: 37% 29% 28%  7%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.087] [info]    [ffmpeg] [libx264 @ 0000017BAD698A00] kb/s:10004.69
[2022-05-15 12:52:49.087] [info]    
[2022-05-15 12:52:49.305] [info]    ffmpeg[ch1/20220515122248.mp4] Uninitialized.
[2022-05-15 12:52:49.991] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515122249.mp4\r\n
[2022-05-15 12:52:49.992] [info]    ffmpeg[ch2/20220515122249.mp4] Uninitialized.
[2022-05-15 12:52:49.992] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 12:52:49.995] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515125249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 12:52:49.995] [info]    ffmpeg[ch2/20220515125249.mp4] Initialized.
[2022-05-15 12:52:49.995] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 12:52:50.005] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] using SAR=1/1
[2022-05-15 12:52:50.005] [info]    
[2022-05-15 12:52:50.006] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 12:52:50.006] [info]    
[2022-05-15 12:52:50.011] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 12:52:50.011] [info]    
[2022-05-15 12:52:50.019] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8E00] Pure channel mapping detected:
[2022-05-15 12:52:50.019] [info]    [ffmpeg]  0
[2022-05-15 12:52:50.019] [info]    [ffmpeg]  1
[2022-05-15 12:52:50.019] [info]    [ffmpeg] 
[2022-05-15 12:52:50.019] [info]    
[2022-05-15 12:52:50.021] [warning] ffmpeg[ch2/20220515125249.mp4] Unused option s=1920:1080
[2022-05-15 12:52:50.116] [info]    [ffmpeg] [aac @ 0000017B1D008500] Qavg: 422.015
[2022-05-15 12:52:50.116] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] frame I:520   Avg QP:22.12  size: 93861
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] frame P:23445 Avg QP:18.76  size: 60567
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] frame B:66035 Avg QP:22.33  size:  9476
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] consecutive B-frames:  1.1%  2.8%  1.4% 94.7%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] mb I  I16..4: 27.6% 47.5% 24.9%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] mb P  I16..4:  9.9% 12.5%  2.5%  P16..4: 35.2% 12.6%  7.9%  0.0%  0.0%    skip:19.5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] mb B  I16..4:  1.2%  0.9%  0.1%  B16..8: 13.6%  3.8%  0.3%  direct: 9.6%  skip:70.4%  L0:48.1% L1:39.1% BI:12.8%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] 8x8 transform intra:48.4% inter:31.5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] coded y,uvDC,uvAC intra: 55.2% 49.0% 17.7% inter: 11.4% 11.4% 0.6%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] i16 v,h,dc,p: 41% 29% 20% 10%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 24% 27%  4%  5%  5%  5%  5%  5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 25% 14%  5%  7%  7%  7%  5%  5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] i8c dc,h,v,p: 52% 24% 19%  5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] Weighted P-Frames: Y:1.6% UV:0.5%
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC732240] kb/s:9309.27
[2022-05-15 12:52:50.128] [info]    
[2022-05-15 12:52:50.352] [info]    ffmpeg[ch2/20220515122249.mp4] Uninitialized.
[2022-05-15 13:22:48.995] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515125248.mp4\r\n
[2022-05-15 13:22:48.996] [info]    ffmpeg[ch1/20220515125248.mp4] Uninitialized.
[2022-05-15 13:22:48.996] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 13:22:48.998] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515132248.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 13:22:48.999] [info]    ffmpeg[ch1/20220515132248.mp4] Initialized.
[2022-05-15 13:22:48.999] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 13:22:49.009] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] using SAR=1/1
[2022-05-15 13:22:49.009] [info]    
[2022-05-15 13:22:49.010] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 13:22:49.010] [info]    
[2022-05-15 13:22:49.017] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 13:22:49.017] [info]    
[2022-05-15 13:22:49.023] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA400] Pure channel mapping detected:
[2022-05-15 13:22:49.023] [info]    [ffmpeg]  0
[2022-05-15 13:22:49.023] [info]    [ffmpeg]  1
[2022-05-15 13:22:49.023] [info]    [ffmpeg] 
[2022-05-15 13:22:49.023] [info]    
[2022-05-15 13:22:49.025] [warning] ffmpeg[ch1/20220515132248.mp4] Unused option s=1920:1080
[2022-05-15 13:22:49.069] [info]    [ffmpeg] [aac @ 0000017BAC741000] Qavg: 2393.527
[2022-05-15 13:22:49.069] [info]    
[2022-05-15 13:22:49.076] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] frame I:360   Avg QP:26.60  size:111913
[2022-05-15 13:22:49.076] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] frame P:22746 Avg QP:14.35  size: 67660
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] frame B:66894 Avg QP:19.84  size:  8632
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] consecutive B-frames:  0.7%  0.4%  0.2% 98.6%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] mb I  I16..4: 46.7% 14.0% 39.3%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] mb P  I16..4:  2.0%  0.9%  0.9%  P16..4: 29.3%  5.1%  5.2%  0.0%  0.0%    skip:56.6%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  5.0%  2.0%  0.5%  direct: 4.8%  skip:87.5%  L0:27.9% L1:54.2% BI:17.9%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] 8x8 transform intra:20.8% inter:22.7%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] coded y,uvDC,uvAC intra: 54.0% 58.0% 44.5% inter: 9.4% 6.8% 2.8%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] i16 v,h,dc,p: 53% 36%  4%  7%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 26% 20%  4%  5%  6%  5%  6%  7%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 32% 10%  4%  5%  5%  5%  5%  5%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] i8c dc,h,v,p: 36% 31% 27%  6%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.077] [info]    [ffmpeg] [libx264 @ 0000017BAC73EB80] kb/s:9585.34
[2022-05-15 13:22:49.077] [info]    
[2022-05-15 13:22:49.302] [info]    ffmpeg[ch1/20220515125248.mp4] Uninitialized.
[2022-05-15 13:22:49.984] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515125249.mp4\r\n
[2022-05-15 13:22:49.984] [info]    ffmpeg[ch2/20220515125249.mp4] Uninitialized.
[2022-05-15 13:22:49.984] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 13:22:49.987] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515132249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 13:22:49.987] [info]    ffmpeg[ch2/20220515132249.mp4] Initialized.
[2022-05-15 13:22:49.987] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 13:22:49.997] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] using SAR=1/1
[2022-05-15 13:22:49.997] [info]    
[2022-05-15 13:22:49.998] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 13:22:49.998] [info]    
[2022-05-15 13:22:50.007] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 13:22:50.007] [info]    
[2022-05-15 13:22:50.024] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8400] Pure channel mapping detected:
[2022-05-15 13:22:50.024] [info]    [ffmpeg]  0
[2022-05-15 13:22:50.024] [info]    [ffmpeg]  1
[2022-05-15 13:22:50.024] [info]    [ffmpeg] 
[2022-05-15 13:22:50.024] [info]    
[2022-05-15 13:22:50.026] [warning] ffmpeg[ch2/20220515132249.mp4] Unused option s=1920:1080
[2022-05-15 13:22:50.066] [info]    [ffmpeg] [aac @ 0000017BF5CD6300] Qavg: 360.996
[2022-05-15 13:22:50.066] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] frame I:478   Avg QP:21.17  size: 97898
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] frame P:23580 Avg QP:18.84  size: 59993
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] frame B:65941 Avg QP:22.57  size: 10310
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] consecutive B-frames:  1.0%  3.6%  1.3% 94.2%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] mb I  I16..4: 27.2% 45.7% 27.1%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] mb P  I16..4: 11.2% 15.5%  2.9%  P16..4: 30.7% 12.6%  7.3%  0.0%  0.0%    skip:19.8%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] mb B  I16..4:  1.3%  1.0%  0.1%  B16..8: 14.6%  4.1%  0.4%  direct: 9.1%  skip:69.4%  L0:49.1% L1:37.6% BI:13.3%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] 8x8 transform intra:50.3% inter:30.7%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] coded y,uvDC,uvAC intra: 55.7% 49.9% 18.2% inter: 10.5% 10.4% 0.4%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] i16 v,h,dc,p: 42% 28% 20% 10%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.077] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 24% 26%  4%  5%  5%  5%  5%  5%
[2022-05-15 13:22:50.077] [info]    
[2022-05-15 13:22:50.078] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 25% 14%  5%  7%  7%  7%  5%  5%
[2022-05-15 13:22:50.078] [info]    
[2022-05-15 13:22:50.078] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] i8c dc,h,v,p: 52% 24% 19%  5%
[2022-05-15 13:22:50.078] [info]    
[2022-05-15 13:22:50.078] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] Weighted P-Frames: Y:1.4% UV:0.2%
[2022-05-15 13:22:50.078] [info]    
[2022-05-15 13:22:50.078] [info]    [ffmpeg] [libx264 @ 0000017BF5FD4E00] kb/s:9516.74
[2022-05-15 13:22:50.078] [info]    
[2022-05-15 13:22:50.336] [info]    ffmpeg[ch2/20220515125249.mp4] Uninitialized.
[2022-05-15 13:52:48.997] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515132248.mp4\r\n
[2022-05-15 13:52:48.998] [info]    ffmpeg[ch1/20220515132248.mp4] Uninitialized.
[2022-05-15 13:52:48.998] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 13:52:49.001] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515135249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 13:52:49.003] [info]    ffmpeg[ch1/20220515135249.mp4] Initialized.
[2022-05-15 13:52:49.003] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 13:52:49.014] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] using SAR=1/1
[2022-05-15 13:52:49.014] [info]    
[2022-05-15 13:52:49.014] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 13:52:49.014] [info]    
[2022-05-15 13:52:49.020] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 13:52:49.020] [info]    
[2022-05-15 13:52:49.025] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7E00] Pure channel mapping detected:
[2022-05-15 13:52:49.025] [info]    [ffmpeg]  0
[2022-05-15 13:52:49.025] [info]    [ffmpeg]  1
[2022-05-15 13:52:49.025] [info]    [ffmpeg] 
[2022-05-15 13:52:49.025] [info]    
[2022-05-15 13:52:49.027] [warning] ffmpeg[ch1/20220515135249.mp4] Unused option s=1920:1080
[2022-05-15 13:52:49.095] [info]    [ffmpeg] [aac @ 0000017BACB1FA40] Qavg: 3550.801
[2022-05-15 13:52:49.095] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] frame I:360   Avg QP:28.96  size:113944
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] frame P:22820 Avg QP:16.55  size: 69492
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] frame B:66820 Avg QP:22.67  size:  9744
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] consecutive B-frames:  0.7%  0.8%  0.3% 98.3%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] mb I  I16..4: 40.0% 18.3% 41.7%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] mb P  I16..4:  2.4%  1.1%  1.6%  P16..4: 28.5%  6.7%  6.8%  0.0%  0.0%    skip:52.8%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] mb B  I16..4:  0.3%  0.1%  0.1%  B16..8:  5.4%  2.3%  0.6%  direct: 5.1%  skip:86.0%  L0:30.8% L1:47.7% BI:21.5%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] 8x8 transform intra:22.4% inter:21.5%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] coded y,uvDC,uvAC intra: 55.1% 60.6% 39.9% inter: 9.7% 7.4% 2.5%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] i16 v,h,dc,p: 52% 36%  4%  8%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 22% 17%  5%  6%  7%  6%  7%  6%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] i8c dc,h,v,p: 36% 29% 28%  6%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.099] [info]    [ffmpeg] [libx264 @ 0000017B556D0200] kb/s:10124.08
[2022-05-15 13:52:49.099] [info]    
[2022-05-15 13:52:49.183] [info]    ffmpeg[ch1/20220515132248.mp4] Uninitialized.
[2022-05-15 13:52:49.996] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515132249.mp4\r\n
[2022-05-15 13:52:49.997] [info]    ffmpeg[ch2/20220515132249.mp4] Uninitialized.
[2022-05-15 13:52:49.997] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 13:52:50.000] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515135249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 13:52:50.001] [info]    ffmpeg[ch2/20220515135249.mp4] Initialized.
[2022-05-15 13:52:50.001] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 13:52:50.011] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] using SAR=1/1
[2022-05-15 13:52:50.011] [info]    
[2022-05-15 13:52:50.012] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 13:52:50.012] [info]    
[2022-05-15 13:52:50.017] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 13:52:50.017] [info]    
[2022-05-15 13:52:50.021] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8600] Pure channel mapping detected:
[2022-05-15 13:52:50.021] [info]    [ffmpeg]  0
[2022-05-15 13:52:50.021] [info]    [ffmpeg]  1
[2022-05-15 13:52:50.021] [info]    [ffmpeg] 
[2022-05-15 13:52:50.021] [info]    
[2022-05-15 13:52:50.022] [warning] ffmpeg[ch2/20220515135249.mp4] Unused option s=1920:1080
[2022-05-15 13:52:50.104] [info]    [ffmpeg] [aac @ 0000017B76F84480] Qavg: 452.158
[2022-05-15 13:52:50.104] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] frame I:453   Avg QP:22.71  size: 97939
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] frame P:23760 Avg QP:18.43  size: 59033
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] frame B:65787 Avg QP:22.16  size:  9439
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] consecutive B-frames:  1.2%  3.1%  2.2% 93.4%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] mb I  I16..4: 29.6% 41.8% 28.6%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] mb P  I16..4:  9.8% 11.5%  3.1%  P16..4: 30.0% 11.3%  7.4%  0.0%  0.0%    skip:27.0%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] mb B  I16..4:  1.5%  1.0%  0.1%  B16..8: 12.3%  3.7%  0.4%  direct: 8.5%  skip:72.6%  L0:43.9% L1:41.5% BI:14.6%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] 8x8 transform intra:45.1% inter:26.5%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] coded y,uvDC,uvAC intra: 59.3% 53.4% 20.4% inter: 10.2% 10.1% 1.0%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] i16 v,h,dc,p: 35% 28% 25% 12%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 21% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 23% 14%  5%  7%  7%  6%  5%  5%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] i8c dc,h,v,p: 48% 26% 21%  5%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] Weighted P-Frames: Y:1.2% UV:0.2%
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.109] [info]    [ffmpeg] [libx264 @ 0000017BACA23900] kb/s:9190.93
[2022-05-15 13:52:50.109] [info]    
[2022-05-15 13:52:50.214] [info]    ffmpeg[ch2/20220515132249.mp4] Uninitialized.
[2022-05-15 14:22:49.013] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515135249.mp4\r\n
[2022-05-15 14:22:49.014] [info]    ffmpeg[ch1/20220515135249.mp4] Uninitialized.
[2022-05-15 14:22:49.014] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 14:22:49.016] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515142249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 14:22:49.016] [info]    ffmpeg[ch1/20220515142249.mp4] Initialized.
[2022-05-15 14:22:49.016] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 14:22:49.021] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] using SAR=1/1
[2022-05-15 14:22:49.021] [info]    
[2022-05-15 14:22:49.021] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 14:22:49.021] [info]    
[2022-05-15 14:22:49.024] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 14:22:49.024] [info]    
[2022-05-15 14:22:49.028] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9400] Pure channel mapping detected:
[2022-05-15 14:22:49.029] [info]    [ffmpeg]  0
[2022-05-15 14:22:49.029] [info]    [ffmpeg]  1
[2022-05-15 14:22:49.029] [info]    [ffmpeg] 
[2022-05-15 14:22:49.029] [info]    
[2022-05-15 14:22:49.030] [warning] ffmpeg[ch1/20220515142249.mp4] Unused option s=1920:1080
[2022-05-15 14:22:49.100] [info]    [ffmpeg] [aac @ 0000017BACE1D740] Qavg: 7077.988
[2022-05-15 14:22:49.100] [info]    
[2022-05-15 14:22:49.103] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] frame I:361   Avg QP:29.66  size:115005
[2022-05-15 14:22:49.103] [info]    
[2022-05-15 14:22:49.103] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] frame P:22804 Avg QP:16.91  size: 70500
[2022-05-15 14:22:49.103] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] frame B:66836 Avg QP:23.19  size:  9657
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] consecutive B-frames:  0.7%  0.6%  0.3% 98.4%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] mb I  I16..4: 39.2% 18.2% 42.6%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] mb P  I16..4:  2.0%  0.7%  1.1%  P16..4: 29.1%  6.5%  7.0%  0.0%  0.0%    skip:53.5%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.7%  2.1%  0.6%  direct: 5.2%  skip:87.1%  L0:28.6% L1:47.0% BI:24.4%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] 8x8 transform intra:19.2% inter:20.1%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] coded y,uvDC,uvAC intra: 53.8% 59.4% 42.4% inter: 9.7% 7.1% 2.5%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] i16 v,h,dc,p: 53% 38%  4%  5%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 26% 18%  4%  4%  5%  5%  7%  6%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28%  9%  4%  5%  6%  5%  6%  6%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] i8c dc,h,v,p: 36% 32% 27%  6%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.104] [info]    [ffmpeg] [libx264 @ 0000017B1CBA0100] kb/s:10198.36
[2022-05-15 14:22:49.104] [info]    
[2022-05-15 14:22:49.199] [info]    ffmpeg[ch1/20220515135249.mp4] Uninitialized.
[2022-05-15 14:22:50.015] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515135249.mp4\r\n
[2022-05-15 14:22:50.016] [info]    ffmpeg[ch2/20220515135249.mp4] Uninitialized.
[2022-05-15 14:22:50.016] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 14:22:50.017] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515142250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 14:22:50.018] [info]    ffmpeg[ch2/20220515142250.mp4] Initialized.
[2022-05-15 14:22:50.018] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 14:22:50.023] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] using SAR=1/1
[2022-05-15 14:22:50.023] [info]    
[2022-05-15 14:22:50.024] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 14:22:50.024] [info]    
[2022-05-15 14:22:50.030] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 14:22:50.030] [info]    
[2022-05-15 14:22:50.039] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8D00] Pure channel mapping detected:
[2022-05-15 14:22:50.039] [info]    [ffmpeg]  0
[2022-05-15 14:22:50.039] [info]    [ffmpeg]  1
[2022-05-15 14:22:50.039] [info]    [ffmpeg] 
[2022-05-15 14:22:50.039] [info]    
[2022-05-15 14:22:50.042] [warning] ffmpeg[ch2/20220515142250.mp4] Unused option s=1920:1080
[2022-05-15 14:22:50.122] [info]    [ffmpeg] [aac @ 0000017BF5E38440] Qavg: 409.633
[2022-05-15 14:22:50.122] [info]    
[2022-05-15 14:22:50.128] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] frame I:438   Avg QP:23.00  size: 99320
[2022-05-15 14:22:50.128] [info]    
[2022-05-15 14:22:50.128] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] frame P:23395 Avg QP:19.17  size: 60220
[2022-05-15 14:22:50.128] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] frame B:66168 Avg QP:23.20  size:  9996
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] consecutive B-frames:  1.0%  2.5%  1.2% 95.3%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] mb I  I16..4: 27.3% 44.3% 28.4%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] mb P  I16..4:  9.3% 12.2%  2.8%  P16..4: 30.7% 11.5%  7.6%  0.0%  0.0%    skip:25.9%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] mb B  I16..4:  1.6%  1.3%  0.1%  B16..8: 12.3%  3.9%  0.4%  direct: 8.2%  skip:72.2%  L0:42.9% L1:41.7% BI:15.4%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] 8x8 transform intra:48.1% inter:28.9%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] coded y,uvDC,uvAC intra: 55.7% 54.3% 17.7% inter: 10.7% 9.2% 0.5%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] i16 v,h,dc,p: 35% 30% 23% 11%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 22% 27%  4%  5%  6%  5%  5%  5%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 26% 13%  5%  7%  7%  6%  5%  5%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] i8c dc,h,v,p: 47% 27% 21%  6%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] Weighted P-Frames: Y:1.2% UV:0.2%
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.129] [info]    [ffmpeg] [libx264 @ 0000017BF5A2B440] kb/s:9394.32
[2022-05-15 14:22:50.129] [info]    
[2022-05-15 14:22:50.247] [info]    ffmpeg[ch2/20220515135249.mp4] Uninitialized.
[2022-05-15 14:52:49.016] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515142249.mp4\r\n
[2022-05-15 14:52:49.016] [info]    ffmpeg[ch1/20220515142249.mp4] Uninitialized.
[2022-05-15 14:52:49.016] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 14:52:49.018] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515145249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 14:52:49.018] [info]    ffmpeg[ch1/20220515145249.mp4] Initialized.
[2022-05-15 14:52:49.018] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 14:52:49.023] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] using SAR=1/1
[2022-05-15 14:52:49.023] [info]    
[2022-05-15 14:52:49.023] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 14:52:49.023] [info]    
[2022-05-15 14:52:49.028] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 14:52:49.028] [info]    
[2022-05-15 14:52:49.036] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7800] Pure channel mapping detected:
[2022-05-15 14:52:49.037] [info]    [ffmpeg]  0
[2022-05-15 14:52:49.037] [info]    [ffmpeg]  1
[2022-05-15 14:52:49.037] [info]    [ffmpeg] 
[2022-05-15 14:52:49.037] [info]    
[2022-05-15 14:52:49.038] [warning] ffmpeg[ch1/20220515145249.mp4] Unused option s=1920:1080
[2022-05-15 14:52:49.093] [info]    [ffmpeg] [aac @ 0000017B556D0B00] Qavg: 12165.797
[2022-05-15 14:52:49.093] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] frame I:360   Avg QP:29.23  size:113483
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] frame P:22732 Avg QP:16.34  size: 69262
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] frame B:66908 Avg QP:22.52  size:  9522
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] consecutive B-frames:  0.8%  0.3%  0.1% 98.8%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] mb I  I16..4: 40.2% 17.7% 42.1%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] mb P  I16..4:  2.1%  0.7%  1.3%  P16..4: 29.1%  5.9%  6.4%  0.0%  0.0%    skip:54.5%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] mb B  I16..4:  0.2%  0.1%  0.1%  B16..8:  4.7%  2.1%  0.6%  direct: 5.0%  skip:87.3%  L0:35.0% L1:42.5% BI:22.5%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] 8x8 transform intra:18.8% inter:21.3%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] coded y,uvDC,uvAC intra: 53.6% 58.5% 41.1% inter: 9.5% 7.1% 2.7%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] i16 v,h,dc,p: 55% 36%  3%  5%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 26% 16%  5%  5%  5%  5%  6%  6%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 30%  9%  4%  5%  6%  6%  5%  5%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] i8c dc,h,v,p: 35% 31% 29%  5%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.098] [info]    [ffmpeg] [libx264 @ 0000017B76E91940] kb/s:10010.69
[2022-05-15 14:52:49.098] [info]    
[2022-05-15 14:52:49.198] [info]    ffmpeg[ch1/20220515142249.mp4] Uninitialized.
[2022-05-15 14:52:50.021] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515142250.mp4\r\n
[2022-05-15 14:52:50.021] [info]    ffmpeg[ch2/20220515142250.mp4] Uninitialized.
[2022-05-15 14:52:50.021] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 14:52:50.023] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515145250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 14:52:50.023] [info]    ffmpeg[ch2/20220515145250.mp4] Initialized.
[2022-05-15 14:52:50.023] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 14:52:50.029] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] using SAR=1/1
[2022-05-15 14:52:50.029] [info]    
[2022-05-15 14:52:50.029] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 14:52:50.029] [info]    
[2022-05-15 14:52:50.039] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 14:52:50.039] [info]    
[2022-05-15 14:52:50.048] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8700] Pure channel mapping detected:
[2022-05-15 14:52:50.048] [info]    [ffmpeg]  0
[2022-05-15 14:52:50.048] [info]    [ffmpeg]  1
[2022-05-15 14:52:50.048] [info]    [ffmpeg] 
[2022-05-15 14:52:50.048] [info]    
[2022-05-15 14:52:50.050] [warning] ffmpeg[ch2/20220515145250.mp4] Unused option s=1920:1080
[2022-05-15 14:52:50.131] [info]    [ffmpeg] [aac @ 0000017B1D079900] Qavg: 354.058
[2022-05-15 14:52:50.131] [info]    
[2022-05-15 14:52:50.136] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] frame I:415   Avg QP:23.25  size:100511
[2022-05-15 14:52:50.136] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] frame P:23246 Avg QP:19.06  size: 60500
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] frame B:66339 Avg QP:22.51  size:  9951
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] consecutive B-frames:  0.8%  2.6%  0.6% 96.0%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] mb I  I16..4: 28.2% 43.7% 28.1%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] mb P  I16..4:  9.4% 13.1%  2.6%  P16..4: 32.7% 11.2%  7.4%  0.0%  0.0%    skip:23.6%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] mb B  I16..4:  1.6%  1.3%  0.1%  B16..8: 13.0%  3.8%  0.4%  direct: 8.8%  skip:71.0%  L0:39.9% L1:46.7% BI:13.3%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] 8x8 transform intra:49.6% inter:28.0%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] coded y,uvDC,uvAC intra: 59.6% 54.3% 18.4% inter: 10.7% 10.9% 0.5%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] i16 v,h,dc,p: 32% 28% 28% 12%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 21% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 23% 14%  5%  7%  7%  6%  5%  5%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] i8c dc,h,v,p: 48% 26% 21%  5%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] Weighted P-Frames: Y:0.4% UV:0.2%
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.137] [info]    [ffmpeg] [libx264 @ 0000017BACB4AAC0] kb/s:9369.94
[2022-05-15 14:52:50.137] [info]    
[2022-05-15 14:52:50.246] [info]    ffmpeg[ch2/20220515142250.mp4] Uninitialized.
[2022-05-15 15:22:49.022] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515145249.mp4\r\n
[2022-05-15 15:22:49.023] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 15:22:49.023] [info]    ffmpeg[ch1/20220515145249.mp4] Uninitialized.
[2022-05-15 15:22:49.024] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515152249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 15:22:49.025] [info]    ffmpeg[ch1/20220515152249.mp4] Initialized.
[2022-05-15 15:22:49.025] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 15:22:49.032] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] using SAR=1/1
[2022-05-15 15:22:49.032] [info]    
[2022-05-15 15:22:49.033] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 15:22:49.033] [info]    
[2022-05-15 15:22:49.043] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 15:22:49.043] [info]    
[2022-05-15 15:22:49.053] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA000] Pure channel mapping detected:
[2022-05-15 15:22:49.054] [info]    [ffmpeg]  0
[2022-05-15 15:22:49.054] [info]    [ffmpeg]  1
[2022-05-15 15:22:49.054] [info]    [ffmpeg] 
[2022-05-15 15:22:49.054] [info]    
[2022-05-15 15:22:49.056] [warning] ffmpeg[ch1/20220515152249.mp4] Unused option s=1920:1080
[2022-05-15 15:22:49.092] [info]    [ffmpeg] [aac @ 0000017BAC988240] Qavg: 8107.520
[2022-05-15 15:22:49.092] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] frame I:360   Avg QP:27.35  size:113272
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] frame P:22722 Avg QP:14.39  size: 67897
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] frame B:66918 Avg QP:20.66  size:  9286
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] consecutive B-frames:  0.8%  0.2%  0.1% 98.9%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] mb I  I16..4: 42.3% 17.1% 40.6%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] mb P  I16..4:  1.8%  0.5%  0.9%  P16..4: 29.0%  5.3%  5.8%  0.0%  0.0%    skip:56.6%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.7%  1.9%  0.6%  direct: 4.6%  skip:88.0%  L0:38.6% L1:40.7% BI:20.7%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] 8x8 transform intra:17.9% inter:21.6%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] coded y,uvDC,uvAC intra: 54.7% 58.7% 43.8% inter: 9.1% 6.7% 2.6%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] i16 v,h,dc,p: 56% 34%  5%  4%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 23% 22%  4%  5%  5%  5%  5%  5%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 32% 27%  9%  4%  5%  6%  6%  5%  5%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] i8c dc,h,v,p: 37% 29% 29%  5%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.097] [info]    [ffmpeg] [libx264 @ 0000017BF62802C0] kb/s:9799.79
[2022-05-15 15:22:49.097] [info]    
[2022-05-15 15:22:49.208] [info]    ffmpeg[ch1/20220515145249.mp4] Uninitialized.
[2022-05-15 15:22:50.040] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515145250.mp4\r\n
[2022-05-15 15:22:50.042] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 15:22:50.042] [info]    ffmpeg[ch2/20220515145250.mp4] Uninitialized.
[2022-05-15 15:22:50.046] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515152250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 15:22:50.047] [info]    ffmpeg[ch2/20220515152250.mp4] Initialized.
[2022-05-15 15:22:50.047] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 15:22:50.055] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] using SAR=1/1
[2022-05-15 15:22:50.055] [info]    
[2022-05-15 15:22:50.055] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 15:22:50.055] [info]    
[2022-05-15 15:22:50.060] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 15:22:50.060] [info]    
[2022-05-15 15:22:50.064] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9300] Pure channel mapping detected:
[2022-05-15 15:22:50.064] [info]    [ffmpeg]  0
[2022-05-15 15:22:50.064] [info]    [ffmpeg]  1
[2022-05-15 15:22:50.064] [info]    [ffmpeg] 
[2022-05-15 15:22:50.064] [info]    
[2022-05-15 15:22:50.065] [warning] ffmpeg[ch2/20220515152250.mp4] Unused option s=1920:1080
[2022-05-15 15:22:50.147] [info]    [ffmpeg] [aac @ 0000017B76D4F180] Qavg: 325.129
[2022-05-15 15:22:50.147] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] frame I:409   Avg QP:22.34  size: 99625
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] frame P:23270 Avg QP:18.66  size: 59338
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] frame B:66322 Avg QP:22.02  size: 10017
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] consecutive B-frames:  0.8%  2.4%  1.1% 95.7%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] mb I  I16..4: 30.1% 43.5% 26.4%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] mb P  I16..4: 11.0% 12.7%  2.5%  P16..4: 30.2% 11.1%  7.1%  0.0%  0.0%    skip:25.5%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] mb B  I16..4:  2.0%  1.2%  0.1%  B16..8: 12.4%  3.9%  0.4%  direct: 9.1%  skip:70.9%  L0:46.7% L1:40.0% BI:13.3%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] 8x8 transform intra:45.7% inter:27.6%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] coded y,uvDC,uvAC intra: 58.8% 54.8% 20.4% inter: 10.3% 10.5% 0.5%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] i16 v,h,dc,p: 35% 26% 28% 12%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 20% 31%  4%  4%  6%  4%  5%  4%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 24% 15%  5%  7%  7%  6%  5%  5%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] i8c dc,h,v,p: 48% 26% 21%  5%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] Weighted P-Frames: Y:0.8% UV:0.1%
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.153] [info]    [ffmpeg] [libx264 @ 0000017B76D4DA80] kb/s:9270.55
[2022-05-15 15:22:50.153] [info]    
[2022-05-15 15:22:50.288] [info]    ffmpeg[ch2/20220515145250.mp4] Uninitialized.
[2022-05-15 15:52:49.021] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515152249.mp4\r\n
[2022-05-15 15:52:49.021] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 15:52:49.021] [info]    ffmpeg[ch1/20220515152249.mp4] Uninitialized.
[2022-05-15 15:52:49.023] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515155249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 15:52:49.023] [info]    ffmpeg[ch1/20220515155249.mp4] Initialized.
[2022-05-15 15:52:49.023] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 15:52:49.028] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] using SAR=1/1
[2022-05-15 15:52:49.028] [info]    
[2022-05-15 15:52:49.029] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 15:52:49.029] [info]    
[2022-05-15 15:52:49.039] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 15:52:49.039] [info]    
[2022-05-15 15:52:49.051] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7900] Pure channel mapping detected:
[2022-05-15 15:52:49.051] [info]    [ffmpeg]  0
[2022-05-15 15:52:49.051] [info]    [ffmpeg]  1
[2022-05-15 15:52:49.051] [info]    [ffmpeg] 
[2022-05-15 15:52:49.051] [info]    
[2022-05-15 15:52:49.054] [warning] ffmpeg[ch1/20220515155249.mp4] Unused option s=1920:1080
[2022-05-15 15:52:49.092] [info]    [ffmpeg] [aac @ 0000017BACB8D080] Qavg: 6184.645
[2022-05-15 15:52:49.092] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] frame I:360   Avg QP:26.58  size:113054
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] frame P:22795 Avg QP:13.53  size: 67325
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] frame B:66845 Avg QP:20.06  size:  8638
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] consecutive B-frames:  0.8%  0.6%  0.1% 98.6%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] mb I  I16..4: 45.7% 15.0% 39.3%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] mb P  I16..4:  2.1%  0.6%  0.9%  P16..4: 28.7%  5.0%  5.1%  0.0%  0.0%    skip:57.6%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.3%  1.8%  0.5%  direct: 4.5%  skip:88.6%  L0:36.3% L1:43.9% BI:19.8%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] 8x8 transform intra:18.1% inter:19.3%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] coded y,uvDC,uvAC intra: 55.4% 57.9% 44.1% inter: 8.8% 6.4% 2.8%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] i16 v,h,dc,p: 55% 32%  9%  5%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 18% 33%  3%  5%  6%  4%  4%  4%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 34% 27% 10%  4%  5%  5%  6%  4%  5%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] i8c dc,h,v,p: 38% 26% 31%  4%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BAC741480] kb/s:9567.86
[2022-05-15 15:52:49.097] [info]    
[2022-05-15 15:52:49.202] [info]    ffmpeg[ch1/20220515152249.mp4] Uninitialized.
[2022-05-15 15:52:50.053] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515152250.mp4\r\n
[2022-05-15 15:52:50.054] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 15:52:50.054] [info]    ffmpeg[ch2/20220515152250.mp4] Uninitialized.
[2022-05-15 15:52:50.055] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515155250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 15:52:50.056] [info]    ffmpeg[ch2/20220515155250.mp4] Initialized.
[2022-05-15 15:52:50.056] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 15:52:50.060] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] using SAR=1/1
[2022-05-15 15:52:50.060] [info]    
[2022-05-15 15:52:50.060] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 15:52:50.060] [info]    
[2022-05-15 15:52:50.063] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 15:52:50.063] [info]    
[2022-05-15 15:52:50.070] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9800] Pure channel mapping detected:
[2022-05-15 15:52:50.070] [info]    [ffmpeg]  0
[2022-05-15 15:52:50.070] [info]    [ffmpeg]  1
[2022-05-15 15:52:50.070] [info]    [ffmpeg] 
[2022-05-15 15:52:50.070] [info]    
[2022-05-15 15:52:50.073] [warning] ffmpeg[ch2/20220515155250.mp4] Unused option s=1920:1080
[2022-05-15 15:52:50.161] [info]    [ffmpeg] [aac @ 0000017BF6656D80] Qavg: 349.089
[2022-05-15 15:52:50.161] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] frame I:437   Avg QP:22.58  size:103099
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] frame P:23139 Avg QP:17.28  size: 63139
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] frame B:66424 Avg QP:19.93  size: 10006
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] consecutive B-frames:  1.0%  1.7%  0.5% 96.8%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] mb I  I16..4: 32.9% 38.9% 28.2%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] mb P  I16..4: 10.0% 10.1%  2.8%  P16..4: 35.1% 14.2%  9.5%  0.0%  0.0%    skip:18.3%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] mb B  I16..4:  1.3%  0.7%  0.1%  B16..8: 15.6%  4.8%  0.4%  direct:10.4%  skip:66.7%  L0:51.5% L1:36.7% BI:11.8%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] 8x8 transform intra:42.0% inter:28.7%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] coded y,uvDC,uvAC intra: 54.7% 66.2% 34.2% inter: 11.8% 14.8% 1.0%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] i16 v,h,dc,p: 42% 26% 24%  7%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 19% 21% 30%  5%  5%  5%  5%  5%  5%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 29% 21% 17%  5%  7%  7%  5%  5%  4%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] i8c dc,h,v,p: 46% 26% 22%  6%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] Weighted P-Frames: Y:0.2% UV:0.1%
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.168] [info]    [ffmpeg] [libx264 @ 0000017C5A4DB100] kb/s:9647.32
[2022-05-15 15:52:50.168] [info]    
[2022-05-15 15:52:50.293] [info]    ffmpeg[ch2/20220515152250.mp4] Uninitialized.
[2022-05-15 16:22:49.026] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515155249.mp4\r\n
[2022-05-15 16:22:49.027] [info]    ffmpeg[ch1/20220515155249.mp4] Uninitialized.
[2022-05-15 16:22:49.027] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 16:22:49.028] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515162249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 16:22:49.029] [info]    ffmpeg[ch1/20220515162249.mp4] Initialized.
[2022-05-15 16:22:49.029] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 16:22:49.038] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] using SAR=1/1
[2022-05-15 16:22:49.038] [info]    
[2022-05-15 16:22:49.039] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 16:22:49.039] [info]    
[2022-05-15 16:22:49.047] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 16:22:49.047] [info]    
[2022-05-15 16:22:49.054] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8A00] Pure channel mapping detected:
[2022-05-15 16:22:49.054] [info]    [ffmpeg]  0
[2022-05-15 16:22:49.054] [info]    [ffmpeg]  1
[2022-05-15 16:22:49.054] [info]    [ffmpeg] 
[2022-05-15 16:22:49.054] [info]    
[2022-05-15 16:22:49.056] [warning] ffmpeg[ch1/20220515162249.mp4] Unused option s=1920:1080
[2022-05-15 16:22:49.108] [info]    [ffmpeg] [aac @ 0000017BF5A7BE80] Qavg: 7252.725
[2022-05-15 16:22:49.108] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] frame I:361   Avg QP:26.16  size:111328
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] frame P:23087 Avg QP:13.74  size: 66735
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] frame B:66553 Avg QP:19.95  size:  8546
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] consecutive B-frames:  0.7%  1.9%  0.2% 97.2%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] mb I  I16..4: 46.9% 13.9% 39.2%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] mb P  I16..4:  2.2%  0.6%  0.7%  P16..4: 27.9%  4.6%  4.9%  0.0%  0.0%    skip:59.1%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.1%  1.7%  0.4%  direct: 4.7%  skip:88.7%  L0:34.9% L1:45.1% BI:20.0%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] 8x8 transform intra:18.8% inter:19.5%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] coded y,uvDC,uvAC intra: 55.0% 56.4% 44.3% inter: 8.8% 6.4% 2.8%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] i16 v,h,dc,p: 55% 32%  8%  5%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 20% 35%  3%  4%  5%  4%  3%  4%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 32% 30% 10%  4%  5%  5%  6%  4%  5%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] i8c dc,h,v,p: 40% 28% 28%  4%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.115] [info]    [ffmpeg] [libx264 @ 0000017BF635D600] kb/s:9553.86
[2022-05-15 16:22:49.115] [info]    
[2022-05-15 16:22:49.219] [info]    ffmpeg[ch1/20220515155249.mp4] Uninitialized.
[2022-05-15 16:22:50.056] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515155250.mp4\r\n
[2022-05-15 16:22:50.056] [info]    ffmpeg[ch2/20220515155250.mp4] Uninitialized.
[2022-05-15 16:22:50.056] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 16:22:50.058] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515162250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 16:22:50.058] [info]    ffmpeg[ch2/20220515162250.mp4] Initialized.
[2022-05-15 16:22:50.058] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 16:22:50.062] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] using SAR=1/1
[2022-05-15 16:22:50.062] [info]    
[2022-05-15 16:22:50.062] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 16:22:50.062] [info]    
[2022-05-15 16:22:50.065] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 16:22:50.065] [info]    
[2022-05-15 16:22:50.070] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8B00] Pure channel mapping detected:
[2022-05-15 16:22:50.070] [info]    [ffmpeg]  0
[2022-05-15 16:22:50.070] [info]    [ffmpeg]  1
[2022-05-15 16:22:50.070] [info]    [ffmpeg] 
[2022-05-15 16:22:50.070] [info]    
[2022-05-15 16:22:50.073] [warning] ffmpeg[ch2/20220515162250.mp4] Unused option s=1920:1080
[2022-05-15 16:22:50.178] [info]    [ffmpeg] [aac @ 0000017BACA0D8C0] Qavg: 287.269
[2022-05-15 16:22:50.178] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] frame I:410   Avg QP:23.19  size:105996
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] frame P:23436 Avg QP:17.78  size: 63015
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] frame B:66154 Avg QP:20.50  size: 10162
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] consecutive B-frames:  1.3%  1.9%  0.6% 96.2%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] mb I  I16..4: 29.1% 39.4% 31.5%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] mb P  I16..4:  8.4%  8.8%  2.2%  P16..4: 37.4% 15.3% 10.0%  0.0%  0.0%    skip:18.0%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] mb B  I16..4:  1.0%  0.7%  0.1%  B16..8: 15.8%  4.7%  0.4%  direct:10.3%  skip:67.0%  L0:35.1% L1:52.5% BI:12.4%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] 8x8 transform intra:43.5% inter:30.2%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] coded y,uvDC,uvAC intra: 55.2% 64.3% 33.7% inter: 12.4% 14.5% 1.0%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] i16 v,h,dc,p: 45% 26% 22%  7%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 21% 27%  4%  5%  5%  5%  5%  5%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 22% 15%  5%  7%  7%  6%  5%  4%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] i8c dc,h,v,p: 47% 25% 22%  6%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] Weighted P-Frames: Y:0.7% UV:0.3%
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.182] [info]    [ffmpeg] [libx264 @ 0000017B76D20680] kb/s:9744.71
[2022-05-15 16:22:50.182] [info]    
[2022-05-15 16:22:50.314] [info]    ffmpeg[ch2/20220515155250.mp4] Uninitialized.
[2022-05-15 16:52:49.012] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515162249.mp4\r\n
[2022-05-15 16:52:49.014] [info]    ffmpeg[ch1/20220515162249.mp4] Uninitialized.
[2022-05-15 16:52:49.014] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 16:52:49.015] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515165249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 16:52:49.015] [info]    ffmpeg[ch1/20220515165249.mp4] Initialized.
[2022-05-15 16:52:49.015] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 16:52:49.020] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] using SAR=1/1
[2022-05-15 16:52:49.020] [info]    
[2022-05-15 16:52:49.021] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 16:52:49.021] [info]    
[2022-05-15 16:52:49.024] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 16:52:49.024] [info]    
[2022-05-15 16:52:49.030] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7E00] Pure channel mapping detected:
[2022-05-15 16:52:49.030] [info]    [ffmpeg]  0
[2022-05-15 16:52:49.030] [info]    [ffmpeg]  1
[2022-05-15 16:52:49.030] [info]    [ffmpeg] 
[2022-05-15 16:52:49.030] [info]    
[2022-05-15 16:52:49.032] [warning] ffmpeg[ch1/20220515165249.mp4] Unused option s=1920:1080
[2022-05-15 16:52:49.095] [info]    [ffmpeg] [aac @ 0000017BF60B00C0] Qavg: 7712.049
[2022-05-15 16:52:49.095] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] frame I:360   Avg QP:26.91  size:112875
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] frame P:22855 Avg QP:13.05  size: 68546
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] frame B:66784 Avg QP:19.54  size:  8149
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] consecutive B-frames:  0.7%  1.0%  0.3% 98.0%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] mb I  I16..4: 47.3% 13.9% 38.8%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] mb P  I16..4:  2.6%  0.6%  0.7%  P16..4: 29.3%  4.0%  4.6%  0.0%  0.0%    skip:58.2%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.2%  1.6%  0.4%  direct: 4.4%  skip:89.2%  L0:26.9% L1:56.3% BI:16.7%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] 8x8 transform intra:17.6% inter:19.6%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] coded y,uvDC,uvAC intra: 55.0% 52.3% 41.0% inter: 8.6% 6.7% 3.2%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] i16 v,h,dc,p: 57% 34%  6%  3%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 17% 35%  4%  4%  5%  4%  5%  4%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] i8c dc,h,v,p: 39% 30% 26%  4%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.100] [info]    [ffmpeg] [libx264 @ 0000017B1C8ACC00] kb/s:9562.35
[2022-05-15 16:52:49.100] [info]    
[2022-05-15 16:52:49.215] [info]    ffmpeg[ch1/20220515162249.mp4] Uninitialized.
[2022-05-15 16:52:50.054] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515162250.mp4\r\n
[2022-05-15 16:52:50.055] [info]    ffmpeg[ch2/20220515162250.mp4] Uninitialized.
[2022-05-15 16:52:50.055] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 16:52:50.056] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515165250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 16:52:50.057] [info]    ffmpeg[ch2/20220515165250.mp4] Initialized.
[2022-05-15 16:52:50.057] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 16:52:50.061] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] using SAR=1/1
[2022-05-15 16:52:50.061] [info]    
[2022-05-15 16:52:50.061] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 16:52:50.061] [info]    
[2022-05-15 16:52:50.065] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 16:52:50.065] [info]    
[2022-05-15 16:52:50.068] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7F00] Pure channel mapping detected:
[2022-05-15 16:52:50.068] [info]    [ffmpeg]  0
[2022-05-15 16:52:50.068] [info]    [ffmpeg]  1
[2022-05-15 16:52:50.068] [info]    [ffmpeg] 
[2022-05-15 16:52:50.068] [info]    
[2022-05-15 16:52:50.070] [warning] ffmpeg[ch2/20220515165250.mp4] Unused option s=1920:1080
[2022-05-15 16:52:50.178] [info]    [ffmpeg] [aac @ 0000017BF652FE40] Qavg: 448.032
[2022-05-15 16:52:50.178] [info]    
[2022-05-15 16:52:50.181] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] frame I:422   Avg QP:22.98  size:103982
[2022-05-15 16:52:50.181] [info]    
[2022-05-15 16:52:50.181] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] frame P:23488 Avg QP:19.91  size: 59070
[2022-05-15 16:52:50.181] [info]    
[2022-05-15 16:52:50.181] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] frame B:66090 Avg QP:23.08  size:  8253
[2022-05-15 16:52:50.181] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] consecutive B-frames:  0.9%  3.2%  0.8% 95.1%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] mb I  I16..4: 17.3% 50.1% 32.6%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] mb P  I16..4:  9.6% 20.5%  2.6%  P16..4: 34.0% 14.5%  8.4%  0.0%  0.0%    skip:10.4%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] mb B  I16..4:  1.4%  1.8%  0.0%  B16..8: 14.2%  3.2%  0.2%  direct:10.4%  skip:68.8%  L0:53.2% L1:36.0% BI:10.8%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] 8x8 transform intra:60.5% inter:37.1%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] coded y,uvDC,uvAC intra: 59.9% 51.1% 16.7% inter: 12.0% 13.1% 0.4%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] i16 v,h,dc,p: 34% 29% 26% 12%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 16% 21% 26%  5%  7%  6%  7%  6%  7%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 22% 13%  6%  9%  8%  8%  6%  6%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] i8c dc,h,v,p: 55% 24% 16%  4%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] Weighted P-Frames: Y:3.8% UV:0.7%
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BAC9F1F80] kb/s:8785.61
[2022-05-15 16:52:50.182] [info]    
[2022-05-15 16:52:50.307] [info]    ffmpeg[ch2/20220515162250.mp4] Uninitialized.
[2022-05-15 17:22:49.025] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515165249.mp4\r\n
[2022-05-15 17:22:49.025] [info]    ffmpeg[ch1/20220515165249.mp4] Uninitialized.
[2022-05-15 17:22:49.025] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 17:22:49.028] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515172249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 17:22:49.028] [info]    ffmpeg[ch1/20220515172249.mp4] Initialized.
[2022-05-15 17:22:49.028] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 17:22:49.037] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] using SAR=1/1
[2022-05-15 17:22:49.037] [info]    
[2022-05-15 17:22:49.038] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 17:22:49.038] [info]    
[2022-05-15 17:22:49.046] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 17:22:49.046] [info]    
[2022-05-15 17:22:49.059] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7300] Pure channel mapping detected:
[2022-05-15 17:22:49.059] [info]    [ffmpeg]  0
[2022-05-15 17:22:49.059] [info]    [ffmpeg]  1
[2022-05-15 17:22:49.059] [info]    [ffmpeg] 
[2022-05-15 17:22:49.059] [info]    
[2022-05-15 17:22:49.061] [warning] ffmpeg[ch1/20220515172249.mp4] Unused option s=1920:1080
[2022-05-15 17:22:49.090] [info]    [ffmpeg] [aac @ 0000017B1C92CA80] Qavg: 6692.734
[2022-05-15 17:22:49.090] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] frame I:360   Avg QP:26.19  size:112335
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] frame P:22725 Avg QP:13.07  size: 67531
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] frame B:66915 Avg QP:19.66  size:  8360
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] consecutive B-frames:  0.8%  0.2%  0.1% 98.9%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] mb I  I16..4: 48.6% 13.2% 38.3%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] mb P  I16..4:  2.6%  0.6%  0.6%  P16..4: 27.9%  4.1%  4.7%  0.0%  0.0%    skip:59.6%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] mb B  I16..4:  0.1%  0.1%  0.0%  B16..8:  4.1%  1.6%  0.4%  direct: 4.6%  skip:89.0%  L0:37.6% L1:44.2% BI:18.1%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] 8x8 transform intra:16.8% inter:19.2%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] coded y,uvDC,uvAC intra: 54.5% 49.6% 39.3% inter: 8.5% 6.3% 3.0%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] i16 v,h,dc,p: 58% 33%  6%  2%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 17% 41%  3%  3%  4%  3%  3%  4%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 29% 10%  4%  5%  5%  5%  5%  5%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] i8c dc,h,v,p: 41% 30% 25%  4%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.096] [info]    [ffmpeg] [libx264 @ 0000017B1CAF0D40] kb/s:9486.69
[2022-05-15 17:22:49.096] [info]    
[2022-05-15 17:22:49.192] [info]    ffmpeg[ch1/20220515165249.mp4] Uninitialized.
[2022-05-15 17:22:50.046] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515165250.mp4\r\n
[2022-05-15 17:22:50.047] [info]    ffmpeg[ch2/20220515165250.mp4] Uninitialized.
[2022-05-15 17:22:50.047] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 17:22:50.048] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515172250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 17:22:50.049] [info]    ffmpeg[ch2/20220515172250.mp4] Initialized.
[2022-05-15 17:22:50.049] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 17:22:50.056] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] using SAR=1/1
[2022-05-15 17:22:50.056] [info]    
[2022-05-15 17:22:50.057] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 17:22:50.057] [info]    
[2022-05-15 17:22:50.060] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 17:22:50.060] [info]    
[2022-05-15 17:22:50.064] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FAB00] Pure channel mapping detected:
[2022-05-15 17:22:50.064] [info]    [ffmpeg]  0
[2022-05-15 17:22:50.064] [info]    [ffmpeg]  1
[2022-05-15 17:22:50.064] [info]    [ffmpeg] 
[2022-05-15 17:22:50.064] [info]    
[2022-05-15 17:22:50.065] [warning] ffmpeg[ch2/20220515172250.mp4] Unused option s=1920:1080
[2022-05-15 17:22:50.183] [info]    [ffmpeg] [aac @ 0000017BAD045200] Qavg: 686.674
[2022-05-15 17:22:50.183] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] frame I:453   Avg QP:20.72  size:101527
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] frame P:23570 Avg QP:18.94  size: 57448
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] frame B:65977 Avg QP:22.43  size:  8177
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] consecutive B-frames:  0.9%  3.6%  1.2% 94.3%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] mb I  I16..4: 19.8% 48.4% 31.8%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] mb P  I16..4: 10.1% 23.4%  3.2%  P16..4: 29.2% 13.6%  7.6%  0.0%  0.0%    skip:12.9%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] mb B  I16..4:  1.6%  2.3%  0.0%  B16..8: 13.9%  3.1%  0.2%  direct: 9.5%  skip:69.4%  L0:56.8% L1:32.5% BI:10.7%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] 8x8 transform intra:62.0% inter:37.0%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] coded y,uvDC,uvAC intra: 60.8% 52.0% 16.5% inter: 10.9% 11.9% 0.3%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] i16 v,h,dc,p: 34% 30% 23% 13%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 15% 24% 23%  5%  6%  6%  7%  5%  7%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 25% 13%  6%  9%  7%  9%  6%  6%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] i8c dc,h,v,p: 55% 25% 15%  4%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] Weighted P-Frames: Y:2.7% UV:1.0%
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.186] [info]    [ffmpeg] [libx264 @ 0000017BAD047200] kb/s:8620.15
[2022-05-15 17:22:50.186] [info]    
[2022-05-15 17:22:50.315] [info]    ffmpeg[ch2/20220515165250.mp4] Uninitialized.
[2022-05-15 17:52:49.021] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515172249.mp4\r\n
[2022-05-15 17:52:49.021] [info]    ffmpeg[ch1/20220515172249.mp4] Uninitialized.
[2022-05-15 17:52:49.021] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 17:52:49.023] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515175249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 17:52:49.023] [info]    ffmpeg[ch1/20220515175249.mp4] Initialized.
[2022-05-15 17:52:49.023] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 17:52:49.029] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] using SAR=1/1
[2022-05-15 17:52:49.029] [info]    
[2022-05-15 17:52:49.029] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 17:52:49.029] [info]    
[2022-05-15 17:52:49.038] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 17:52:49.038] [info]    
[2022-05-15 17:52:49.050] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA200] Pure channel mapping detected:
[2022-05-15 17:52:49.050] [info]    [ffmpeg]  0
[2022-05-15 17:52:49.050] [info]    [ffmpeg]  1
[2022-05-15 17:52:49.050] [info]    [ffmpeg] 
[2022-05-15 17:52:49.050] [info]    
[2022-05-15 17:52:49.053] [warning] ffmpeg[ch1/20220515175249.mp4] Unused option s=1920:1080
[2022-05-15 17:52:49.090] [info]    [ffmpeg] [aac @ 0000017C59D40080] Qavg: 6031.709
[2022-05-15 17:52:49.090] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] frame I:360   Avg QP:25.96  size:110906
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] frame P:23006 Avg QP:13.69  size: 66237
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] frame B:66633 Avg QP:20.03  size:  8981
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] consecutive B-frames:  0.7%  1.7%  0.3% 97.3%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] mb I  I16..4: 46.8% 14.5% 38.7%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] mb P  I16..4:  2.8%  0.9%  0.9%  P16..4: 25.7%  4.6%  5.1%  0.0%  0.0%    skip:59.8%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] mb B  I16..4:  0.2%  0.1%  0.0%  B16..8:  4.8%  1.9%  0.5%  direct: 4.6%  skip:87.9%  L0:25.7% L1:55.8% BI:18.5%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] 8x8 transform intra:20.7% inter:19.4%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] coded y,uvDC,uvAC intra: 59.0% 54.4% 42.0% inter: 8.6% 6.5% 2.8%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] i16 v,h,dc,p: 55% 33%  8%  4%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 22% 34%  3%  4%  4%  4%  4%  5%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28% 10%  4%  6%  6%  5%  5%  5%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] i8c dc,h,v,p: 41% 29% 25%  5%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.095] [info]    [ffmpeg] [libx264 @ 0000017BF5F266C0] kb/s:9609.90
[2022-05-15 17:52:49.095] [info]    
[2022-05-15 17:52:49.197] [info]    ffmpeg[ch1/20220515172249.mp4] Uninitialized.
[2022-05-15 17:52:50.054] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515172250.mp4\r\n
[2022-05-15 17:52:50.054] [info]    ffmpeg[ch2/20220515172250.mp4] Uninitialized.
[2022-05-15 17:52:50.054] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 17:52:50.056] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515175250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 17:52:50.056] [info]    ffmpeg[ch2/20220515175250.mp4] Initialized.
[2022-05-15 17:52:50.056] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 17:52:50.061] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] using SAR=1/1
[2022-05-15 17:52:50.061] [info]    
[2022-05-15 17:52:50.061] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 17:52:50.061] [info]    
[2022-05-15 17:52:50.064] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 17:52:50.064] [info]    
[2022-05-15 17:52:50.067] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7F00] Pure channel mapping detected:
[2022-05-15 17:52:50.068] [info]    [ffmpeg]  0
[2022-05-15 17:52:50.068] [info]    [ffmpeg]  1
[2022-05-15 17:52:50.068] [info]    [ffmpeg] 
[2022-05-15 17:52:50.068] [info]    
[2022-05-15 17:52:50.069] [warning] ffmpeg[ch2/20220515175250.mp4] Unused option s=1920:1080
[2022-05-15 17:52:50.157] [info]    [ffmpeg] [aac @ 0000017BF60BC240] Qavg: 402.536
[2022-05-15 17:52:50.157] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] frame I:513   Avg QP:21.15  size: 96864
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] frame P:23596 Avg QP:18.13  size: 59096
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] frame B:65891 Avg QP:20.97  size: 10760
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] consecutive B-frames:  1.5%  2.4%  1.1% 95.1%
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] mb I  I16..4: 29.5% 43.1% 27.4%
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] mb P  I16..4: 11.5% 13.9%  3.0%  P16..4: 31.8% 12.9%  7.9%  0.0%  0.0%    skip:19.0%
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] mb B  I16..4:  1.8%  1.2%  0.1%  B16..8: 15.5%  4.6%  0.4%  direct:11.5%  skip:65.0%  L0:46.8% L1:41.0% BI:12.3%
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.165] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] 8x8 transform intra:46.3% inter:27.2%
[2022-05-15 17:52:50.165] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] coded y,uvDC,uvAC intra: 52.9% 57.3% 22.7% inter: 11.5% 13.9% 0.5%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] i16 v,h,dc,p: 40% 28% 23% 10%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 20% 25%  5%  6%  7%  6%  6%  5%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 15%  5%  7%  7%  6%  6%  4%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] i8c dc,h,v,p: 50% 24% 20%  6%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] Weighted P-Frames: Y:0.4% UV:0.2%
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.166] [info]    [ffmpeg] [libx264 @ 0000017BAD0F6840] kb/s:9569.39
[2022-05-15 17:52:50.166] [info]    
[2022-05-15 17:52:50.291] [info]    ffmpeg[ch2/20220515172250.mp4] Uninitialized.
[2022-05-15 18:22:49.016] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515175249.mp4\r\n
[2022-05-15 18:22:49.017] [info]    ffmpeg[ch1/20220515175249.mp4] Uninitialized.
[2022-05-15 18:22:49.017] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 18:22:49.018] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515182249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 18:22:49.018] [info]    ffmpeg[ch1/20220515182249.mp4] Initialized.
[2022-05-15 18:22:49.018] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 18:22:49.023] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] using SAR=1/1
[2022-05-15 18:22:49.023] [info]    
[2022-05-15 18:22:49.024] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 18:22:49.024] [info]    
[2022-05-15 18:22:49.029] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 18:22:49.029] [info]    
[2022-05-15 18:22:49.041] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9200] Pure channel mapping detected:
[2022-05-15 18:22:49.041] [info]    [ffmpeg]  0
[2022-05-15 18:22:49.041] [info]    [ffmpeg]  1
[2022-05-15 18:22:49.041] [info]    [ffmpeg] 
[2022-05-15 18:22:49.041] [info]    
[2022-05-15 18:22:49.044] [warning] ffmpeg[ch1/20220515182249.mp4] Unused option s=1920:1080
[2022-05-15 18:22:49.097] [info]    [ffmpeg] [aac @ 0000017BAC98EB00] Qavg: 7134.663
[2022-05-15 18:22:49.097] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] frame I:360   Avg QP:24.90  size:111293
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] frame P:22823 Avg QP:13.59  size: 66349
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] frame B:66817 Avg QP:19.47  size:  8893
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] consecutive B-frames:  0.8%  0.7%  0.1% 98.4%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] mb I  I16..4: 47.8% 14.1% 38.0%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] mb P  I16..4:  2.9%  1.1%  0.9%  P16..4: 25.7%  4.8%  5.2%  0.0%  0.0%    skip:59.4%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  4.9%  2.0%  0.5%  direct: 4.8%  skip:87.4%  L0:38.2% L1:41.9% BI:19.9%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] 8x8 transform intra:24.8% inter:20.3%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] coded y,uvDC,uvAC intra: 63.5% 56.5% 45.3% inter: 8.8% 6.3% 2.5%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] i16 v,h,dc,p: 54% 32%  9%  6%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 19% 23% 36%  3%  3%  3%  4%  3%  5%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 27% 11%  4%  6%  6%  6%  5%  5%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] i8c dc,h,v,p: 43% 28% 23%  5%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.101] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] kb/s:9549.18
[2022-05-15 18:22:49.101] [info]    
[2022-05-15 18:22:49.217] [info]    ffmpeg[ch1/20220515175249.mp4] Uninitialized.
[2022-05-15 18:22:50.057] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515175250.mp4\r\n
[2022-05-15 18:22:50.057] [info]    ffmpeg[ch2/20220515175250.mp4] Uninitialized.
[2022-05-15 18:22:50.057] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 18:22:50.059] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515182250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 18:22:50.060] [info]    ffmpeg[ch2/20220515182250.mp4] Initialized.
[2022-05-15 18:22:50.060] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 18:22:50.064] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] using SAR=1/1
[2022-05-15 18:22:50.064] [info]    
[2022-05-15 18:22:50.065] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 18:22:50.065] [info]    
[2022-05-15 18:22:50.070] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 18:22:50.070] [info]    
[2022-05-15 18:22:50.081] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8000] Pure channel mapping detected:
[2022-05-15 18:22:50.081] [info]    [ffmpeg]  0
[2022-05-15 18:22:50.081] [info]    [ffmpeg]  1
[2022-05-15 18:22:50.081] [info]    [ffmpeg] 
[2022-05-15 18:22:50.081] [info]    
[2022-05-15 18:22:50.083] [warning] ffmpeg[ch2/20220515182250.mp4] Unused option s=1920:1080
[2022-05-15 18:22:50.166] [info]    [ffmpeg] [aac @ 0000017BF60BB900] Qavg: 595.810
[2022-05-15 18:22:50.166] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] frame I:539   Avg QP:21.50  size: 97290
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] frame P:23672 Avg QP:18.23  size: 61301
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] frame B:65789 Avg QP:21.74  size:  9711
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] consecutive B-frames:  1.1%  3.8%  1.1% 93.9%
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] mb I  I16..4: 26.8% 45.6% 27.7%
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.172] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] mb P  I16..4: 10.2% 15.4%  3.4%  P16..4: 28.9% 13.5%  8.7%  0.0%  0.0%    skip:19.9%
[2022-05-15 18:22:50.172] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] mb B  I16..4:  1.3%  1.3%  0.1%  B16..8: 15.3%  4.5%  0.4%  direct: 9.3%  skip:67.8%  L0:46.3% L1:40.4% BI:13.3%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] 8x8 transform intra:51.7% inter:30.4%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] coded y,uvDC,uvAC intra: 54.0% 58.0% 22.9% inter: 10.8% 13.7% 0.8%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] i16 v,h,dc,p: 46% 27% 17%  9%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 22% 21%  4%  6%  7%  6%  5%  5%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 13%  5%  8%  8%  7%  5%  5%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] i8c dc,h,v,p: 47% 24% 22%  7%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] Weighted P-Frames: Y:1.4% UV:0.6%
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.173] [info]    [ffmpeg] [libx264 @ 0000017B24D6D000] kb/s:9521.77
[2022-05-15 18:22:50.173] [info]    
[2022-05-15 18:22:50.302] [info]    ffmpeg[ch2/20220515175250.mp4] Uninitialized.
[2022-05-15 18:52:49.013] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515182249.mp4\r\n
[2022-05-15 18:52:49.014] [info]    ffmpeg[ch1/20220515182249.mp4] Uninitialized.
[2022-05-15 18:52:49.014] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 18:52:49.016] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515185249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 18:52:49.016] [info]    ffmpeg[ch1/20220515185249.mp4] Initialized.
[2022-05-15 18:52:49.016] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 18:52:49.021] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] using SAR=1/1
[2022-05-15 18:52:49.021] [info]    
[2022-05-15 18:52:49.021] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 18:52:49.021] [info]    
[2022-05-15 18:52:49.025] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 18:52:49.025] [info]    
[2022-05-15 18:52:49.031] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7700] Pure channel mapping detected:
[2022-05-15 18:52:49.031] [info]    [ffmpeg]  0
[2022-05-15 18:52:49.031] [info]    [ffmpeg]  1
[2022-05-15 18:52:49.031] [info]    [ffmpeg] 
[2022-05-15 18:52:49.031] [info]    
[2022-05-15 18:52:49.034] [warning] ffmpeg[ch1/20220515185249.mp4] Unused option s=1920:1080
[2022-05-15 18:52:49.094] [info]    [ffmpeg] [aac @ 0000017BF60BBD80] Qavg: 10487.542
[2022-05-15 18:52:49.094] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] frame I:360   Avg QP:24.98  size:112308
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] frame P:22764 Avg QP:13.01  size: 66618
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] frame B:66876 Avg QP:18.79  size:  9061
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] consecutive B-frames:  0.8%  0.5%  0.2% 98.6%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] mb I  I16..4: 47.9% 14.6% 37.6%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] mb P  I16..4:  3.1%  1.4%  1.4%  P16..4: 26.4%  4.7%  4.6%  0.0%  0.0%    skip:58.3%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] mb B  I16..4:  0.3%  0.3%  0.1%  B16..8:  5.1%  2.1%  0.5%  direct: 4.3%  skip:87.4%  L0:40.2% L1:42.3% BI:17.5%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] 8x8 transform intra:26.2% inter:21.2%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] coded y,uvDC,uvAC intra: 63.8% 58.9% 44.6% inter: 8.7% 6.3% 2.6%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] i16 v,h,dc,p: 50% 33%  8%  8%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 18% 24% 31%  4%  4%  4%  5%  4%  5%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 28% 11%  4%  6%  6%  6%  4%  4%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] i8c dc,h,v,p: 42% 29% 23%  6%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.097] [info]    [ffmpeg] [libx264 @ 0000017BACBAD0C0] kb/s:9612.70
[2022-05-15 18:52:49.097] [info]    
[2022-05-15 18:52:49.215] [info]    ffmpeg[ch1/20220515182249.mp4] Uninitialized.
[2022-05-15 18:52:50.054] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515182250.mp4\r\n
[2022-05-15 18:52:50.055] [info]    ffmpeg[ch2/20220515182250.mp4] Uninitialized.
[2022-05-15 18:52:50.055] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 18:52:50.056] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515185250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 18:52:50.056] [info]    ffmpeg[ch2/20220515185250.mp4] Initialized.
[2022-05-15 18:52:50.056] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 18:52:50.060] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] using SAR=1/1
[2022-05-15 18:52:50.060] [info]    
[2022-05-15 18:52:50.061] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 18:52:50.061] [info]    
[2022-05-15 18:52:50.063] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 18:52:50.063] [info]    
[2022-05-15 18:52:50.067] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7400] Pure channel mapping detected:
[2022-05-15 18:52:50.067] [info]    [ffmpeg]  0
[2022-05-15 18:52:50.067] [info]    [ffmpeg]  1
[2022-05-15 18:52:50.067] [info]    [ffmpeg] 
[2022-05-15 18:52:50.067] [info]    
[2022-05-15 18:52:50.068] [warning] ffmpeg[ch2/20220515185250.mp4] Unused option s=1920:1080
[2022-05-15 18:52:50.166] [info]    [ffmpeg] [aac @ 0000017B1CF9BBC0] Qavg: 559.122
[2022-05-15 18:52:50.166] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] frame I:429   Avg QP:22.85  size:100448
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] frame P:23376 Avg QP:18.74  size: 59363
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] frame B:66195 Avg QP:21.64  size: 10793
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] consecutive B-frames:  1.2%  1.8%  0.8% 96.2%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] mb I  I16..4: 30.0% 40.6% 29.3%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] mb P  I16..4: 10.0% 11.4%  2.9%  P16..4: 33.3% 13.0%  8.4%  0.0%  0.0%    skip:21.0%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] mb B  I16..4:  1.6%  1.1%  0.1%  B16..8: 14.6%  4.5%  0.4%  direct:11.2%  skip:66.4%  L0:44.2% L1:42.6% BI:13.2%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] 8x8 transform intra:44.7% inter:28.0%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] coded y,uvDC,uvAC intra: 52.6% 55.9% 21.0% inter: 12.1% 13.1% 0.5%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] i16 v,h,dc,p: 38% 29% 23% 10%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 20% 25%  5%  6%  7%  6%  6%  5%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 22% 14%  5%  7%  8%  6%  6%  5%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] i8c dc,h,v,p: 51% 24% 20%  6%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] Weighted P-Frames: Y:0.5% UV:0.2%
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.173] [info]    [ffmpeg] [libx264 @ 0000017C5988B9C0] kb/s:9534.28
[2022-05-15 18:52:50.173] [info]    
[2022-05-15 18:52:50.285] [info]    ffmpeg[ch2/20220515182250.mp4] Uninitialized.
[2022-05-15 19:22:49.031] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515185249.mp4\r\n
[2022-05-15 19:22:49.034] [info]    ffmpeg[ch1/20220515185249.mp4] Uninitialized.
[2022-05-15 19:22:49.034] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 19:22:49.036] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515192249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 19:22:49.037] [info]    ffmpeg[ch1/20220515192249.mp4] Initialized.
[2022-05-15 19:22:49.037] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 19:22:49.047] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] using SAR=1/1
[2022-05-15 19:22:49.047] [info]    
[2022-05-15 19:22:49.048] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 19:22:49.048] [info]    
[2022-05-15 19:22:49.056] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 19:22:49.056] [info]    
[2022-05-15 19:22:49.061] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FAF00] Pure channel mapping detected:
[2022-05-15 19:22:49.061] [info]    [ffmpeg]  0
[2022-05-15 19:22:49.061] [info]    [ffmpeg]  1
[2022-05-15 19:22:49.061] [info]    [ffmpeg] 
[2022-05-15 19:22:49.061] [info]    
[2022-05-15 19:22:49.063] [warning] ffmpeg[ch1/20220515192249.mp4] Unused option s=1920:1080
[2022-05-15 19:22:49.108] [info]    [ffmpeg] [aac @ 0000017BAC9A4640] Qavg: 4141.049
[2022-05-15 19:22:49.108] [info]    
[2022-05-15 19:22:49.113] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] frame I:361   Avg QP:26.56  size:111883
[2022-05-15 19:22:49.113] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] frame P:22966 Avg QP:13.41  size: 66492
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] frame B:66674 Avg QP:19.75  size:  8900
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] consecutive B-frames:  0.7%  1.4%  0.2% 97.7%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] mb I  I16..4: 47.4% 13.6% 39.0%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] mb P  I16..4:  2.5%  0.8%  0.6%  P16..4: 28.2%  4.1%  4.5%  0.0%  0.0%    skip:59.4%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  4.0%  1.7%  0.5%  direct: 4.3%  skip:89.1%  L0:35.5% L1:44.3% BI:20.2%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] 8x8 transform intra:23.6% inter:20.3%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] coded y,uvDC,uvAC intra: 59.5% 54.4% 43.9% inter: 8.7% 5.8% 2.5%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] i16 v,h,dc,p: 56% 32%  6%  5%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 17% 27% 34%  3%  3%  3%  4%  3%  5%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 31% 10%  4%  5%  5%  5%  5%  5%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] i8c dc,h,v,p: 43% 29% 23%  5%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017BF5964F40] kb/s:9603.54
[2022-05-15 19:22:49.114] [info]    
[2022-05-15 19:22:49.228] [info]    ffmpeg[ch1/20220515185249.mp4] Uninitialized.
[2022-05-15 19:22:50.071] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515185250.mp4\r\n
[2022-05-15 19:22:50.072] [info]    ffmpeg[ch2/20220515185250.mp4] Uninitialized.
[2022-05-15 19:22:50.072] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 19:22:50.076] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515192250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 19:22:50.076] [info]    ffmpeg[ch2/20220515192250.mp4] Initialized.
[2022-05-15 19:22:50.077] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 19:22:50.088] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] using SAR=1/1
[2022-05-15 19:22:50.088] [info]    
[2022-05-15 19:22:50.088] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 19:22:50.088] [info]    
[2022-05-15 19:22:50.094] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 19:22:50.094] [info]    
[2022-05-15 19:22:50.098] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9E00] Pure channel mapping detected:
[2022-05-15 19:22:50.098] [info]    [ffmpeg]  0
[2022-05-15 19:22:50.098] [info]    [ffmpeg]  1
[2022-05-15 19:22:50.098] [info]    [ffmpeg] 
[2022-05-15 19:22:50.098] [info]    
[2022-05-15 19:22:50.099] [warning] ffmpeg[ch2/20220515192250.mp4] Unused option s=1920:1080
[2022-05-15 19:22:50.174] [info]    [ffmpeg] [aac @ 0000017B76DAE400] Qavg: 320.062
[2022-05-15 19:22:50.174] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] frame I:494   Avg QP:17.14  size: 98742
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] frame P:23997 Avg QP:14.00  size: 59429
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] frame B:65510 Avg QP:19.62  size:  7849
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] consecutive B-frames:  1.1%  3.4%  6.6% 88.9%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] mb I  I16..4: 37.0% 36.8% 26.2%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] mb P  I16..4: 11.1% 11.6%  2.8%  P16..4: 24.8%  8.3%  6.3%  0.0%  0.0%    skip:35.0%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] mb B  I16..4:  1.0%  1.0%  0.0%  B16..8: 10.2%  2.5%  0.2%  direct: 7.9%  skip:77.1%  L0:47.2% L1:42.5% BI:10.2%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] 8x8 transform intra:45.5% inter:25.8%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] coded y,uvDC,uvAC intra: 58.8% 58.5% 29.2% inter: 9.0% 8.5% 0.9%
[2022-05-15 19:22:50.178] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] i16 v,h,dc,p: 47% 24% 21%  9%
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 18% 22% 30%  5%  5%  5%  5%  5%  6%
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 25% 21% 14%  5%  8%  8%  7%  6%  6%
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] i8c dc,h,v,p: 49% 26% 18%  7%
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] Weighted P-Frames: Y:0.8% UV:0.3%
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.179] [info]    [ffmpeg] [libx264 @ 0000017BF63C68C0] kb/s:8840.40
[2022-05-15 19:22:50.179] [info]    
[2022-05-15 19:22:50.308] [info]    ffmpeg[ch2/20220515185250.mp4] Uninitialized.
[2022-05-15 19:52:49.054] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515192249.mp4\r\n
[2022-05-15 19:52:49.055] [info]    ffmpeg[ch1/20220515192249.mp4] Uninitialized.
[2022-05-15 19:52:49.055] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 19:52:49.056] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515195249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 19:52:49.056] [info]    ffmpeg[ch1/20220515195249.mp4] Initialized.
[2022-05-15 19:52:49.056] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 19:52:49.061] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] using SAR=1/1
[2022-05-15 19:52:49.061] [info]    
[2022-05-15 19:52:49.061] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 19:52:49.061] [info]    
[2022-05-15 19:52:49.065] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 19:52:49.065] [info]    
[2022-05-15 19:52:49.072] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9700] Pure channel mapping detected:
[2022-05-15 19:52:49.072] [info]    [ffmpeg]  0
[2022-05-15 19:52:49.072] [info]    [ffmpeg]  1
[2022-05-15 19:52:49.072] [info]    [ffmpeg] 
[2022-05-15 19:52:49.072] [info]    
[2022-05-15 19:52:49.075] [warning] ffmpeg[ch1/20220515195249.mp4] Unused option s=1920:1080
[2022-05-15 19:52:49.137] [info]    [ffmpeg] [aac @ 0000017B1CC1B100] Qavg: 17693.238
[2022-05-15 19:52:49.137] [info]    
[2022-05-15 19:52:49.141] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] frame I:361   Avg QP:24.73  size:111886
[2022-05-15 19:52:49.141] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] frame P:22806 Avg QP:13.42  size: 65393
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] frame B:66834 Avg QP:19.44  size:  9165
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] consecutive B-frames:  0.7%  0.8%  0.3% 98.2%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] mb I  I16..4: 48.0% 14.7% 37.3%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] mb P  I16..4:  2.9%  1.3%  1.5%  P16..4: 25.3%  5.1%  4.9%  0.0%  0.0%    skip:59.0%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] mb B  I16..4:  0.3%  0.2%  0.1%  B16..8:  5.2%  2.1%  0.5%  direct: 4.4%  skip:87.3%  L0:28.1% L1:54.1% BI:17.8%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] 8x8 transform intra:24.4% inter:20.9%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] coded y,uvDC,uvAC intra: 60.7% 61.1% 46.1% inter: 8.5% 6.2% 2.5%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] i16 v,h,dc,p: 50% 36%  7%  7%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 19% 26% 26%  4%  5%  6%  5%  5%  5%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 29% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] i8c dc,h,v,p: 40% 30% 24%  6%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.142] [info]    [ffmpeg] [libx264 @ 0000017BAD0F7180] kb/s:9529.93
[2022-05-15 19:52:49.142] [info]    
[2022-05-15 19:52:49.258] [info]    ffmpeg[ch1/20220515192249.mp4] Uninitialized.
[2022-05-15 19:52:50.073] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515192250.mp4\r\n
[2022-05-15 19:52:50.075] [info]    ffmpeg[ch2/20220515192250.mp4] Uninitialized.
[2022-05-15 19:52:50.075] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 19:52:50.080] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515195250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 19:52:50.081] [info]    ffmpeg[ch2/20220515195250.mp4] Initialized.
[2022-05-15 19:52:50.081] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 19:52:50.089] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] using SAR=1/1
[2022-05-15 19:52:50.089] [info]    
[2022-05-15 19:52:50.090] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 19:52:50.090] [info]    
[2022-05-15 19:52:50.096] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 19:52:50.096] [info]    
[2022-05-15 19:52:50.100] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA400] Pure channel mapping detected:
[2022-05-15 19:52:50.100] [info]    [ffmpeg]  0
[2022-05-15 19:52:50.100] [info]    [ffmpeg]  1
[2022-05-15 19:52:50.100] [info]    [ffmpeg] 
[2022-05-15 19:52:50.100] [info]    
[2022-05-15 19:52:50.101] [warning] ffmpeg[ch2/20220515195250.mp4] Unused option s=1920:1080
[2022-05-15 19:52:50.178] [info]    [ffmpeg] [aac @ 0000017BAC9F0440] Qavg: 440.641
[2022-05-15 19:52:50.178] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] frame I:494   Avg QP:22.55  size: 99474
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] frame P:23881 Avg QP:18.01  size: 61266
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] frame B:65625 Avg QP:21.87  size:  8983
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] consecutive B-frames:  1.3%  3.9%  1.4% 93.4%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] mb I  I16..4: 26.1% 45.5% 28.4%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] mb P  I16..4:  7.9% 10.4%  2.7%  P16..4: 34.8% 13.4%  8.9%  0.0%  0.0%    skip:21.9%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] mb B  I16..4:  0.8%  0.8%  0.1%  B16..8: 13.5%  3.7%  0.4%  direct: 9.2%  skip:71.5%  L0:46.4% L1:40.3% BI:13.4%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] 8x8 transform intra:48.9% inter:31.3%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] coded y,uvDC,uvAC intra: 56.1% 57.4% 25.4% inter: 11.4% 13.1% 0.9%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] i16 v,h,dc,p: 47% 27% 18%  9%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 21% 22%  4%  6%  7%  6%  5%  5%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 26% 23% 13%  5%  8%  8%  7%  5%  5%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] i8c dc,h,v,p: 48% 25% 21%  7%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] Weighted P-Frames: Y:1.0% UV:0.5%
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.182] [info]    [ffmpeg] [libx264 @ 0000017BACB1EC80] kb/s:9340.95
[2022-05-15 19:52:50.182] [info]    
[2022-05-15 19:52:50.306] [info]    ffmpeg[ch2/20220515192250.mp4] Uninitialized.
[2022-05-15 20:22:49.044] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515195249.mp4\r\n
[2022-05-15 20:22:49.045] [info]    ffmpeg[ch1/20220515195249.mp4] Uninitialized.
[2022-05-15 20:22:49.045] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 20:22:49.047] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515202249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 20:22:49.047] [info]    ffmpeg[ch1/20220515202249.mp4] Initialized.
[2022-05-15 20:22:49.047] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 20:22:49.054] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] using SAR=1/1
[2022-05-15 20:22:49.054] [info]    
[2022-05-15 20:22:49.054] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 20:22:49.054] [info]    
[2022-05-15 20:22:49.059] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 20:22:49.059] [info]    
[2022-05-15 20:22:49.063] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA600] Pure channel mapping detected:
[2022-05-15 20:22:49.063] [info]    [ffmpeg]  0
[2022-05-15 20:22:49.063] [info]    [ffmpeg]  1
[2022-05-15 20:22:49.063] [info]    [ffmpeg] 
[2022-05-15 20:22:49.063] [info]    
[2022-05-15 20:22:49.065] [warning] ffmpeg[ch1/20220515202249.mp4] Unused option s=1920:1080
[2022-05-15 20:22:49.125] [info]    [ffmpeg] [aac @ 0000017C59EFF600] Qavg: 4750.762
[2022-05-15 20:22:49.125] [info]    
[2022-05-15 20:22:49.129] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] frame I:360   Avg QP:25.10  size:110862
[2022-05-15 20:22:49.129] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] frame P:22721 Avg QP:14.36  size: 63404
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] frame B:66918 Avg QP:20.72  size:  8929
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] consecutive B-frames:  0.8%  0.2%  0.1% 98.9%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] mb I  I16..4: 48.6% 13.5% 37.9%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] mb P  I16..4:  2.6%  1.1%  1.3%  P16..4: 24.2%  5.0%  5.3%  0.0%  0.0%    skip:60.5%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  5.1%  2.2%  0.5%  direct: 4.4%  skip:87.4%  L0:42.3% L1:36.9% BI:20.8%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] 8x8 transform intra:22.9% inter:20.1%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] coded y,uvDC,uvAC intra: 59.6% 56.2% 38.7% inter: 8.6% 5.6% 2.1%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] i16 v,h,dc,p: 54% 33%  5%  7%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 27% 23%  4%  5%  5%  5%  5%  6%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 27% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] i8c dc,h,v,p: 41% 29% 24%  5%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.130] [info]    [ffmpeg] [libx264 @ 0000017BF5E28BC0] kb/s:9235.83
[2022-05-15 20:22:49.130] [info]    
[2022-05-15 20:22:49.241] [info]    ffmpeg[ch1/20220515195249.mp4] Uninitialized.
[2022-05-15 20:22:50.085] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515195250.mp4\r\n
[2022-05-15 20:22:50.085] [info]    ffmpeg[ch2/20220515195250.mp4] Uninitialized.
[2022-05-15 20:22:50.085] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 20:22:50.089] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515202250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 20:22:50.089] [info]    ffmpeg[ch2/20220515202250.mp4] Initialized.
[2022-05-15 20:22:50.090] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 20:22:50.096] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] using SAR=1/1
[2022-05-15 20:22:50.096] [info]    
[2022-05-15 20:22:50.097] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 20:22:50.097] [info]    
[2022-05-15 20:22:50.100] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 20:22:50.100] [info]    
[2022-05-15 20:22:50.105] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8500] Pure channel mapping detected:
[2022-05-15 20:22:50.105] [info]    [ffmpeg]  0
[2022-05-15 20:22:50.105] [info]    [ffmpeg]  1
[2022-05-15 20:22:50.105] [info]    [ffmpeg] 
[2022-05-15 20:22:50.105] [info]    
[2022-05-15 20:22:50.106] [warning] ffmpeg[ch2/20220515202250.mp4] Unused option s=1920:1080
[2022-05-15 20:22:50.183] [info]    [ffmpeg] [aac @ 0000017BACB5FB40] Qavg: 464.081
[2022-05-15 20:22:50.183] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] frame I:438   Avg QP:21.92  size: 97607
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] frame P:23272 Avg QP:17.94  size: 59849
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] frame B:66290 Avg QP:20.79  size: 10456
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] consecutive B-frames:  1.2%  1.5%  0.8% 96.6%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] mb I  I16..4: 30.2% 42.8% 27.0%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] mb P  I16..4: 10.6% 13.5%  2.7%  P16..4: 32.4% 13.1%  8.3%  0.0%  0.0%    skip:19.5%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] mb B  I16..4:  1.6%  1.2%  0.1%  B16..8: 14.8%  4.5%  0.4%  direct:11.0%  skip:66.5%  L0:47.0% L1:40.5% BI:12.5%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] 8x8 transform intra:48.4% inter:31.9%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] coded y,uvDC,uvAC intra: 53.8% 55.5% 21.6% inter: 11.8% 13.0% 0.6%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] i16 v,h,dc,p: 41% 27% 22% 10%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 20% 28%  4%  5%  6%  5%  5%  5%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 23% 14%  5%  7%  7%  6%  6%  5%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] i8c dc,h,v,p: 49% 25% 20%  6%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] Weighted P-Frames: Y:0.6% UV:0.2%
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.187] [info]    [ffmpeg] [libx264 @ 0000017BAC89D8C0] kb/s:9460.70
[2022-05-15 20:22:50.187] [info]    
[2022-05-15 20:22:50.303] [info]    ffmpeg[ch2/20220515195250.mp4] Uninitialized.
[2022-05-15 20:52:49.046] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515202249.mp4\r\n
[2022-05-15 20:52:49.047] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 20:52:49.047] [info]    ffmpeg[ch1/20220515202249.mp4] Uninitialized.
[2022-05-15 20:52:49.049] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515205249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 20:52:49.050] [info]    ffmpeg[ch1/20220515205249.mp4] Initialized.
[2022-05-15 20:52:49.050] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 20:52:49.058] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] using SAR=1/1
[2022-05-15 20:52:49.058] [info]    
[2022-05-15 20:52:49.058] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 20:52:49.058] [info]    
[2022-05-15 20:52:49.062] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 20:52:49.062] [info]    
[2022-05-15 20:52:49.065] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FAD00] Pure channel mapping detected:
[2022-05-15 20:52:49.065] [info]    [ffmpeg]  0
[2022-05-15 20:52:49.065] [info]    [ffmpeg]  1
[2022-05-15 20:52:49.065] [info]    [ffmpeg] 
[2022-05-15 20:52:49.065] [info]    
[2022-05-15 20:52:49.067] [warning] ffmpeg[ch1/20220515205249.mp4] Unused option s=1920:1080
[2022-05-15 20:52:49.135] [info]    [ffmpeg] [aac @ 0000017BAD0B2F80] Qavg: 24542.639
[2022-05-15 20:52:49.135] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] frame I:360   Avg QP:25.50  size:110737
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] frame P:22768 Avg QP:13.97  size: 62574
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] frame B:66872 Avg QP:20.09  size:  8683
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] consecutive B-frames:  0.8%  0.5%  0.1% 98.7%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] mb I  I16..4: 47.4% 14.1% 38.5%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] mb P  I16..4:  2.5%  1.1%  1.2%  P16..4: 24.7%  4.5%  4.9%  0.0%  0.0%    skip:61.1%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] mb B  I16..4:  0.2%  0.3%  0.1%  B16..8:  4.7%  2.0%  0.5%  direct: 4.1%  skip:88.1%  L0:42.0% L1:37.9% BI:20.0%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] 8x8 transform intra:26.1% inter:20.8%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] coded y,uvDC,uvAC intra: 61.1% 60.2% 45.3% inter: 8.2% 5.8% 2.4%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] i16 v,h,dc,p: 55% 34%  6%  5%
[2022-05-15 20:52:49.139] [info]    
[2022-05-15 20:52:49.140] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 26% 28%  3%  4%  4%  5%  4%  5%
[2022-05-15 20:52:49.140] [info]    
[2022-05-15 20:52:49.140] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 27% 10%  4%  6%  6%  6%  5%  5%
[2022-05-15 20:52:49.140] [info]    
[2022-05-15 20:52:49.140] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] i8c dc,h,v,p: 41% 28% 25%  6%
[2022-05-15 20:52:49.140] [info]    
[2022-05-15 20:52:49.140] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 20:52:49.140] [info]    
[2022-05-15 20:52:49.140] [info]    [ffmpeg] [libx264 @ 0000017BACC8B5C0] kb/s:9089.61
[2022-05-15 20:52:49.140] [info]    
[2022-05-15 20:52:49.259] [info]    ffmpeg[ch1/20220515202249.mp4] Uninitialized.
[2022-05-15 20:52:50.073] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515202250.mp4\r\n
[2022-05-15 20:52:50.076] [info]    ffmpeg[ch2/20220515202250.mp4] Uninitialized.
[2022-05-15 20:52:50.076] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 20:52:50.080] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515205250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 20:52:50.082] [info]    ffmpeg[ch2/20220515205250.mp4] Initialized.
[2022-05-15 20:52:50.082] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 20:52:50.089] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] using SAR=1/1
[2022-05-15 20:52:50.089] [info]    
[2022-05-15 20:52:50.089] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 20:52:50.089] [info]    
[2022-05-15 20:52:50.095] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 20:52:50.095] [info]    
[2022-05-15 20:52:50.100] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9F00] Pure channel mapping detected:
[2022-05-15 20:52:50.100] [info]    [ffmpeg]  0
[2022-05-15 20:52:50.100] [info]    [ffmpeg]  1
[2022-05-15 20:52:50.100] [info]    [ffmpeg] 
[2022-05-15 20:52:50.100] [info]    
[2022-05-15 20:52:50.101] [warning] ffmpeg[ch2/20220515205250.mp4] Unused option s=1920:1080
[2022-05-15 20:52:50.174] [info]    [ffmpeg] [aac @ 0000017B556789C0] Qavg: 278.073
[2022-05-15 20:52:50.174] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] frame I:445   Avg QP:21.06  size:104150
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] frame P:23277 Avg QP:16.84  size: 61996
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] frame B:66277 Avg QP:19.37  size:  9881
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] consecutive B-frames:  1.0%  2.3%  0.7% 96.1%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] mb I  I16..4: 31.9% 37.9% 30.2%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] mb P  I16..4: 10.3% 12.3%  2.8%  P16..4: 32.9% 13.9%  9.1%  0.0%  0.0%    skip:18.7%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] mb B  I16..4:  1.3%  0.9%  0.1%  B16..8: 15.7%  4.7%  0.4%  direct:10.1%  skip:66.9%  L0:51.4% L1:36.5% BI:12.0%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] 8x8 transform intra:46.1% inter:28.3%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] coded y,uvDC,uvAC intra: 56.0% 63.0% 31.3% inter: 11.2% 13.8% 0.9%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] i16 v,h,dc,p: 43% 25% 23%  9%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 20% 27%  5%  5%  6%  6%  6%  5%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 21% 16%  6%  7%  7%  6%  6%  4%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] i8c dc,h,v,p: 47% 24% 22%  7%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] Weighted P-Frames: Y:0.3% UV:0.1%
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.178] [info]    [ffmpeg] [libx264 @ 0000017BF5F35BC0] kb/s:9530.41
[2022-05-15 20:52:50.178] [info]    
[2022-05-15 20:52:50.302] [info]    ffmpeg[ch2/20220515202250.mp4] Uninitialized.
[2022-05-15 21:22:49.052] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515205249.mp4\r\n
[2022-05-15 21:22:49.054] [info]    ffmpeg[ch1/20220515205249.mp4] Uninitialized.
[2022-05-15 21:22:49.054] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 21:22:49.056] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515212249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 21:22:49.056] [info]    ffmpeg[ch1/20220515212249.mp4] Initialized.
[2022-05-15 21:22:49.057] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 21:22:49.062] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] using SAR=1/1
[2022-05-15 21:22:49.062] [info]    
[2022-05-15 21:22:49.062] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 21:22:49.062] [info]    
[2022-05-15 21:22:49.068] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 21:22:49.068] [info]    
[2022-05-15 21:22:49.078] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FA300] Pure channel mapping detected:
[2022-05-15 21:22:49.078] [info]    [ffmpeg]  0
[2022-05-15 21:22:49.078] [info]    [ffmpeg]  1
[2022-05-15 21:22:49.078] [info]    [ffmpeg] 
[2022-05-15 21:22:49.078] [info]    
[2022-05-15 21:22:49.081] [warning] ffmpeg[ch1/20220515212249.mp4] Unused option s=1920:1080
[2022-05-15 21:22:49.134] [info]    [ffmpeg] [aac @ 0000017B1CF9BBC0] Qavg: 693.263
[2022-05-15 21:22:49.134] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] frame I:360   Avg QP:23.76  size:107334
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] frame P:22812 Avg QP:12.28  size: 63487
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] frame B:66828 Avg QP:18.09  size:  8650
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] consecutive B-frames:  0.8%  0.7%  0.1% 98.5%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] mb I  I16..4: 51.4% 12.4% 36.2%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] mb P  I16..4:  2.4%  0.8%  0.8%  P16..4: 25.8%  3.7%  4.1%  0.0%  0.0%    skip:62.3%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  4.3%  1.7%  0.4%  direct: 4.2%  skip:89.0%  L0:38.5% L1:43.4% BI:18.1%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] 8x8 transform intra:24.7% inter:21.0%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] coded y,uvDC,uvAC intra: 58.1% 59.6% 49.6% inter: 8.2% 6.0% 2.8%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] i16 v,h,dc,p: 59% 31%  5%  4%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 25% 31%  3%  3%  3%  4%  4%  5%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 30% 28% 11%  4%  5%  5%  6%  5%  5%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] i8c dc,h,v,p: 44% 27% 23%  6%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D8F140] kb/s:9177.67
[2022-05-15 21:22:49.138] [info]    
[2022-05-15 21:22:49.253] [info]    ffmpeg[ch1/20220515205249.mp4] Uninitialized.
[2022-05-15 21:22:50.100] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515205250.mp4\r\n
[2022-05-15 21:22:50.100] [info]    ffmpeg[ch2/20220515205250.mp4] Uninitialized.
[2022-05-15 21:22:50.100] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 21:22:50.102] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515212250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 21:22:50.102] [info]    ffmpeg[ch2/20220515212250.mp4] Initialized.
[2022-05-15 21:22:50.102] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 21:22:50.107] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] using SAR=1/1
[2022-05-15 21:22:50.107] [info]    
[2022-05-15 21:22:50.108] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 21:22:50.108] [info]    
[2022-05-15 21:22:50.116] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 21:22:50.116] [info]    
[2022-05-15 21:22:50.127] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8800] Pure channel mapping detected:
[2022-05-15 21:22:50.127] [info]    [ffmpeg]  0
[2022-05-15 21:22:50.127] [info]    [ffmpeg]  1
[2022-05-15 21:22:50.127] [info]    [ffmpeg] 
[2022-05-15 21:22:50.127] [info]    
[2022-05-15 21:22:50.129] [warning] ffmpeg[ch2/20220515212250.mp4] Unused option s=1920:1080
[2022-05-15 21:22:50.199] [info]    [ffmpeg] [aac @ 0000017C63696140] Qavg: 351.433
[2022-05-15 21:22:50.199] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] frame I:416   Avg QP:22.64  size:103960
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] frame P:23190 Avg QP:16.88  size: 63581
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] frame B:66395 Avg QP:19.85  size: 10146
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] consecutive B-frames:  1.2%  1.3%  0.4% 97.1%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] mb I  I16..4: 33.6% 36.6% 29.7%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] mb P  I16..4:  9.1%  8.0%  2.4%  P16..4: 34.0% 14.1%  9.5%  0.0%  0.0%    skip:22.9%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] mb B  I16..4:  1.0%  0.6%  0.1%  B16..8: 15.2%  4.7%  0.4%  direct: 9.9%  skip:68.1%  L0:48.7% L1:36.9% BI:14.4%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] 8x8 transform intra:39.8% inter:27.6%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] coded y,uvDC,uvAC intra: 54.9% 64.3% 34.9% inter: 11.9% 13.0% 1.0%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] i16 v,h,dc,p: 47% 25% 21%  7%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 20% 29%  4%  5%  6%  5%  5%  5%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 28% 22% 16%  5%  7%  7%  6%  5%  4%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] i8c dc,h,v,p: 47% 25% 22%  6%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] Weighted P-Frames: Y:0.5% UV:0.1%
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.207] [info]    [ffmpeg] [libx264 @ 0000017C59C3CC00] kb/s:9739.22
[2022-05-15 21:22:50.207] [info]    
[2022-05-15 21:22:50.335] [info]    ffmpeg[ch2/20220515205250.mp4] Uninitialized.
[2022-05-15 21:52:49.050] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515212249.mp4\r\n
[2022-05-15 21:52:49.052] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 21:52:49.052] [info]    ffmpeg[ch1/20220515212249.mp4] Uninitialized.
[2022-05-15 21:52:49.055] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515215249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 21:52:49.056] [info]    ffmpeg[ch1/20220515215249.mp4] Initialized.
[2022-05-15 21:52:49.056] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 21:52:49.060] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] using SAR=1/1
[2022-05-15 21:52:49.060] [info]    
[2022-05-15 21:52:49.061] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 21:52:49.061] [info]    
[2022-05-15 21:52:49.064] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 21:52:49.064] [info]    
[2022-05-15 21:52:49.070] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9A00] Pure channel mapping detected:
[2022-05-15 21:52:49.070] [info]    [ffmpeg]  0
[2022-05-15 21:52:49.070] [info]    [ffmpeg]  1
[2022-05-15 21:52:49.070] [info]    [ffmpeg] 
[2022-05-15 21:52:49.070] [info]    
[2022-05-15 21:52:49.074] [warning] ffmpeg[ch1/20220515215249.mp4] Unused option s=1920:1080
[2022-05-15 21:52:49.134] [info]    [ffmpeg] [aac @ 0000017B1CDCB640] Qavg: 8879.774
[2022-05-15 21:52:49.134] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] frame I:360   Avg QP:23.74  size:108208
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] frame P:22756 Avg QP:11.56  size: 64001
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] frame B:66884 Avg QP:17.40  size:  8832
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] consecutive B-frames:  0.8%  0.4%  0.1% 98.8%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] mb I  I16..4: 52.9% 11.8% 35.4%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] mb P  I16..4:  2.8%  0.9%  0.9%  P16..4: 26.0%  3.4%  3.6%  0.0%  0.0%    skip:62.3%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] mb B  I16..4:  0.2%  0.3%  0.1%  B16..8:  4.2%  1.7%  0.4%  direct: 4.1%  skip:89.2%  L0:39.1% L1:44.8% BI:16.0%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] 8x8 transform intra:24.5% inter:20.4%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] coded y,uvDC,uvAC intra: 56.7% 60.6% 50.3% inter: 7.9% 6.1% 3.1%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] i16 v,h,dc,p: 57% 32%  5%  5%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 25% 29%  4%  3%  4%  4%  4%  5%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 32% 28% 11%  4%  6%  5%  6%  4%  4%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] i8c dc,h,v,p: 41% 29% 24%  5%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5D81FC0] kb/s:9271.41
[2022-05-15 21:52:49.138] [info]    
[2022-05-15 21:52:49.236] [info]    ffmpeg[ch1/20220515212249.mp4] Uninitialized.
[2022-05-15 21:52:50.092] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515212250.mp4\r\n
[2022-05-15 21:52:50.093] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 21:52:50.093] [info]    ffmpeg[ch2/20220515212250.mp4] Uninitialized.
[2022-05-15 21:52:50.095] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515215250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 21:52:50.095] [info]    ffmpeg[ch2/20220515215250.mp4] Initialized.
[2022-05-15 21:52:50.095] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 21:52:50.099] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] using SAR=1/1
[2022-05-15 21:52:50.099] [info]    
[2022-05-15 21:52:50.100] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 21:52:50.100] [info]    
[2022-05-15 21:52:50.103] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 21:52:50.103] [info]    
[2022-05-15 21:52:50.107] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9300] Pure channel mapping detected:
[2022-05-15 21:52:50.107] [info]    [ffmpeg]  0
[2022-05-15 21:52:50.107] [info]    [ffmpeg]  1
[2022-05-15 21:52:50.107] [info]    [ffmpeg] 
[2022-05-15 21:52:50.107] [info]    
[2022-05-15 21:52:50.108] [warning] ffmpeg[ch2/20220515215250.mp4] Unused option s=1920:1080
[2022-05-15 21:52:50.197] [info]    [ffmpeg] [aac @ 0000017BF5ECC7C0] Qavg: 588.953
[2022-05-15 21:52:50.197] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] frame I:439   Avg QP:22.04  size: 96955
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] frame P:23307 Avg QP:18.39  size: 59494
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] frame B:66254 Avg QP:21.40  size: 10720
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] consecutive B-frames:  1.2%  1.6%  0.8% 96.4%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] mb I  I16..4: 30.7% 41.3% 28.0%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] mb P  I16..4: 10.0% 13.2%  2.8%  P16..4: 32.2% 13.1%  8.4%  0.0%  0.0%    skip:20.3%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] mb B  I16..4:  1.5%  1.3%  0.1%  B16..8: 14.8%  4.6%  0.4%  direct:10.7%  skip:66.7%  L0:44.9% L1:41.9% BI:13.3%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] 8x8 transform intra:48.9% inter:31.4%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] coded y,uvDC,uvAC intra: 54.6% 53.5% 18.8% inter: 11.9% 12.3% 0.6%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] i16 v,h,dc,p: 40% 27% 23%  9%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 21% 28%  4%  5%  6%  5%  5%  5%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 13%  5%  7%  7%  6%  6%  5%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] i8c dc,h,v,p: 50% 24% 20%  6%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.205] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] Weighted P-Frames: Y:0.6% UV:0.2%
[2022-05-15 21:52:50.205] [info]    
[2022-05-15 21:52:50.206] [info]    [ffmpeg] [libx264 @ 0000017BF64D6100] kb/s:9508.58
[2022-05-15 21:52:50.206] [info]    
[2022-05-15 21:52:50.333] [info]    ffmpeg[ch2/20220515212250.mp4] Uninitialized.
[2022-05-15 22:22:49.044] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515215249.mp4\r\n
[2022-05-15 22:22:49.045] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 22:22:49.045] [info]    ffmpeg[ch1/20220515215249.mp4] Uninitialized.
[2022-05-15 22:22:49.047] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515222249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 22:22:49.047] [info]    ffmpeg[ch1/20220515222249.mp4] Initialized.
[2022-05-15 22:22:49.047] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 22:22:49.054] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] using SAR=1/1
[2022-05-15 22:22:49.054] [info]    
[2022-05-15 22:22:49.055] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 22:22:49.055] [info]    
[2022-05-15 22:22:49.058] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 22:22:49.058] [info]    
[2022-05-15 22:22:49.064] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7900] Pure channel mapping detected:
[2022-05-15 22:22:49.064] [info]    [ffmpeg]  0
[2022-05-15 22:22:49.064] [info]    [ffmpeg]  1
[2022-05-15 22:22:49.064] [info]    [ffmpeg] 
[2022-05-15 22:22:49.064] [info]    
[2022-05-15 22:22:49.065] [warning] ffmpeg[ch1/20220515222249.mp4] Unused option s=1920:1080
[2022-05-15 22:22:49.108] [info]    [ffmpeg] [aac @ 0000017B770BC180] Qavg: 4311.146
[2022-05-15 22:22:49.108] [info]    
[2022-05-15 22:22:49.113] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] frame I:360   Avg QP:23.66  size:110235
[2022-05-15 22:22:49.113] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] frame P:22735 Avg QP:11.13  size: 65646
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] frame B:66904 Avg QP:16.90  size:  8752
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] consecutive B-frames:  0.8%  0.3%  0.1% 98.9%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] mb I  I16..4: 52.7% 11.5% 35.8%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] mb P  I16..4:  2.6%  0.7%  0.5%  P16..4: 27.4%  3.3%  3.5%  0.0%  0.0%    skip:62.0%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  4.1%  1.5%  0.3%  direct: 4.2%  skip:89.5%  L0:38.8% L1:45.8% BI:15.4%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] 8x8 transform intra:22.6% inter:20.2%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] coded y,uvDC,uvAC intra: 54.0% 57.5% 49.6% inter: 8.1% 6.0% 3.2%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] i16 v,h,dc,p: 57% 34%  6%  3%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 20% 27% 33%  3%  3%  3%  4%  3%  5%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 32% 12%  3%  5%  4%  6%  3%  4%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] i8c dc,h,v,p: 42% 30% 24%  5%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.114] [info]    [ffmpeg] [libx264 @ 0000017B76EB2000] kb/s:9411.87
[2022-05-15 22:22:49.114] [info]    
[2022-05-15 22:22:49.229] [info]    ffmpeg[ch1/20220515215249.mp4] Uninitialized.
[2022-05-15 22:22:50.101] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515215250.mp4\r\n
[2022-05-15 22:22:50.101] [info]    ffmpeg[ch2/20220515215250.mp4] Uninitialized.
[2022-05-15 22:22:50.101] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 22:22:50.103] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515222250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 22:22:50.103] [info]    ffmpeg[ch2/20220515222250.mp4] Initialized.
[2022-05-15 22:22:50.103] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 22:22:50.109] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] using SAR=1/1
[2022-05-15 22:22:50.109] [info]    
[2022-05-15 22:22:50.110] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 22:22:50.110] [info]    
[2022-05-15 22:22:50.119] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 22:22:50.119] [info]    
[2022-05-15 22:22:50.128] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7400] Pure channel mapping detected:
[2022-05-15 22:22:50.128] [info]    [ffmpeg]  0
[2022-05-15 22:22:50.128] [info]    [ffmpeg]  1
[2022-05-15 22:22:50.128] [info]    [ffmpeg] 
[2022-05-15 22:22:50.128] [info]    
[2022-05-15 22:22:50.130] [warning] ffmpeg[ch2/20220515222250.mp4] Unused option s=1920:1080
[2022-05-15 22:22:50.216] [info]    [ffmpeg] [aac @ 0000017BF5E5BEC0] Qavg: 519.294
[2022-05-15 22:22:50.216] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] frame I:520   Avg QP:21.38  size: 97030
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] frame P:24242 Avg QP:17.43  size: 60406
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] frame B:65238 Avg QP:21.07  size: 10011
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] consecutive B-frames:  1.3%  5.8%  1.0% 91.8%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] mb I  I16..4: 30.0% 43.7% 26.3%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] mb P  I16..4: 10.9% 13.6%  3.7%  P16..4: 27.7% 12.6%  8.0%  0.0%  0.0%    skip:23.6%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] mb B  I16..4:  1.3%  1.2%  0.1%  B16..8: 14.9%  4.5%  0.5%  direct: 9.5%  skip:67.9%  L0:38.9% L1:48.1% BI:13.0%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] 8x8 transform intra:47.8% inter:27.9%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] coded y,uvDC,uvAC intra: 54.3% 61.3% 27.8% inter: 10.5% 13.8% 0.9%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] i16 v,h,dc,p: 48% 25% 18%  9%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 24% 21% 21%  4%  6%  7%  6%  5%  5%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 23% 14%  5%  7%  8%  7%  5%  4%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] i8c dc,h,v,p: 46% 24% 23%  7%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] Weighted P-Frames: Y:1.0% UV:0.4%
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.220] [info]    [ffmpeg] [libx264 @ 0000017BF5CAFD40] kb/s:9635.05
[2022-05-15 22:22:50.220] [info]    
[2022-05-15 22:22:50.337] [info]    ffmpeg[ch2/20220515215250.mp4] Uninitialized.
[2022-05-15 22:24:03.298] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 9.13952
[2022-05-15 22:24:03.314] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 9.31135
[2022-05-15 22:24:03.356] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.2595
[2022-05-15 22:24:03.359] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.6314
[2022-05-15 22:24:03.405] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.2795
[2022-05-15 22:24:03.413] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.2995
[2022-05-15 22:24:03.417] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.3195
[2022-05-15 22:24:03.417] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.6914
[2022-05-15 22:24:03.427] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.3395
[2022-05-15 22:24:03.428] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.7514
[2022-05-15 22:24:03.431] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.3595
[2022-05-15 22:24:03.433] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.7714
[2022-05-15 22:24:03.438] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.3795
[2022-05-15 22:24:03.440] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.7914
[2022-05-15 22:24:03.441] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.3995
[2022-05-15 22:24:03.442] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.8114
[2022-05-15 22:24:03.519] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.8314
[2022-05-15 22:24:03.519] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.4195
[2022-05-15 22:24:03.525] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.4395
[2022-05-15 22:24:03.525] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.8514
[2022-05-15 22:24:03.542] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.4595
[2022-05-15 22:24:03.546] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.8714
[2022-05-15 22:24:03.549] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.4795
[2022-05-15 22:24:03.552] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.8914
[2022-05-15 22:24:03.563] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.4995
[2022-05-15 22:24:03.571] [warning] DeckLink Duo 2 [2|1080i5000] out-sync changed: 18.9114
[2022-05-15 22:24:03.571] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.5195
[2022-05-15 22:24:03.586] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.5395
[2022-05-15 22:24:03.594] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.5595
[2022-05-15 22:24:03.610] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.5795
[2022-05-15 22:24:03.616] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.5995
[2022-05-15 22:24:03.631] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.6195
[2022-05-15 22:24:03.637] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.6395
[2022-05-15 22:24:03.650] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.6595
[2022-05-15 22:24:03.654] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.6795
[2022-05-15 22:24:03.670] [warning] DeckLink Duo 2 [4|1080i5000] out-sync changed: 18.6995
[2022-05-15 22:24:29.864] [info]    Received message from 127.0.0.1: play 1-21 [html] c:/casparcg/CMP/off_air_logger_clock/clock_html.html\r\n
[2022-05-15 22:24:30.080] [info]    D3D11: Selected adapter: NVIDIA GeForce RTX 2080 Ti
[2022-05-15 22:24:30.080] [info]    D3D11: Selected feature level: 45312
[2022-05-15 22:24:30.087] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 22:24:31.083] [info]    Received message from 127.0.0.1: play 2-21 [html] c:/casparcg/CMP/off_air_logger_clock/clock_html.html\r\n
[2022-05-15 22:24:31.085] [info]    Sent message to 127.0.0.1:202 PLAY OK\r\n
[2022-05-15 22:52:49.046] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515222249.mp4\r\n
[2022-05-15 22:52:49.047] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 22:52:49.047] [info]    ffmpeg[ch1/20220515222249.mp4] Uninitialized.
[2022-05-15 22:52:49.048] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515225249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 22:52:49.049] [info]    ffmpeg[ch1/20220515225249.mp4] Initialized.
[2022-05-15 22:52:49.049] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 22:52:49.057] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] using SAR=1/1
[2022-05-15 22:52:49.057] [info]    
[2022-05-15 22:52:49.057] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 22:52:49.057] [info]    
[2022-05-15 22:52:49.063] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 22:52:49.063] [info]    
[2022-05-15 22:52:49.067] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F7500] Pure channel mapping detected:
[2022-05-15 22:52:49.068] [info]    [ffmpeg]  0
[2022-05-15 22:52:49.068] [info]    [ffmpeg]  1
[2022-05-15 22:52:49.068] [info]    [ffmpeg] 
[2022-05-15 22:52:49.068] [info]    
[2022-05-15 22:52:49.070] [warning] ffmpeg[ch1/20220515225249.mp4] Unused option s=1920:1080
[2022-05-15 22:52:49.134] [info]    [ffmpeg] [aac @ 0000017B76EB0DC0] Qavg: 7924.683
[2022-05-15 22:52:49.134] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] frame I:357   Avg QP:23.84  size:110104
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] frame P:22603 Avg QP:11.95  size: 64553
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] frame B:66106 Avg QP:17.84  size:  8991
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] consecutive B-frames:  0.8%  0.8%  0.1% 98.4%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] mb I  I16..4: 51.0% 12.7% 36.2%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] mb P  I16..4:  2.5%  1.0%  0.9%  P16..4: 25.8%  3.9%  4.0%  0.0%  0.0%    skip:61.8%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] mb B  I16..4:  0.2%  0.2%  0.1%  B16..8:  4.4%  1.8%  0.4%  direct: 4.3%  skip:88.7%  L0:35.3% L1:47.5% BI:17.2%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] 8x8 transform intra:25.0% inter:20.3%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] coded y,uvDC,uvAC intra: 60.1% 60.9% 50.1% inter: 8.2% 5.9% 2.8%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] i16 v,h,dc,p: 53% 35%  8%  5%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 27% 29%  3%  3%  3%  4%  4%  5%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 32% 30% 11%  4%  5%  5%  5%  4%  5%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] i8c dc,h,v,p: 41% 30% 24%  5%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.139] [info]    [ffmpeg] [libx264 @ 0000017B76EAF700] kb/s:9398.72
[2022-05-15 22:52:49.139] [info]    
[2022-05-15 22:52:49.220] [info]    ffmpeg[ch1/20220515222249.mp4] Uninitialized.
[2022-05-15 22:52:50.109] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515222250.mp4\r\n
[2022-05-15 22:52:50.110] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 22:52:50.110] [info]    ffmpeg[ch2/20220515222250.mp4] Uninitialized.
[2022-05-15 22:52:50.114] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515225250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 22:52:50.116] [info]    ffmpeg[ch2/20220515225250.mp4] Initialized.
[2022-05-15 22:52:50.116] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 22:52:50.127] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] using SAR=1/1
[2022-05-15 22:52:50.127] [info]    
[2022-05-15 22:52:50.128] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 22:52:50.128] [info]    
[2022-05-15 22:52:50.133] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 22:52:50.133] [info]    
[2022-05-15 22:52:50.139] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9FAC00] Pure channel mapping detected:
[2022-05-15 22:52:50.139] [info]    [ffmpeg]  0
[2022-05-15 22:52:50.139] [info]    [ffmpeg]  1
[2022-05-15 22:52:50.139] [info]    [ffmpeg] 
[2022-05-15 22:52:50.139] [info]    
[2022-05-15 22:52:50.140] [warning] ffmpeg[ch2/20220515225250.mp4] Unused option s=1920:1080
[2022-05-15 22:52:50.227] [info]    [ffmpeg] [aac @ 0000017BAC852740] Qavg: 1251.827
[2022-05-15 22:52:50.227] [info]    
[2022-05-15 22:52:50.234] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] frame I:378   Avg QP:23.35  size:104110
[2022-05-15 22:52:50.234] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] frame P:23022 Avg QP:18.42  size: 59972
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] frame B:65668 Avg QP:21.28  size: 10865
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] consecutive B-frames:  1.1%  1.6%  0.7% 96.6%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] mb I  I16..4: 26.9% 42.5% 30.6%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] mb P  I16..4:  9.7% 12.8%  2.8%  P16..4: 32.7% 13.1%  8.5%  0.0%  0.0%    skip:20.5%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] mb B  I16..4:  1.5%  1.3%  0.1%  B16..8: 14.7%  4.6%  0.4%  direct:10.9%  skip:66.5%  L0:45.1% L1:41.7% BI:13.2%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] 8x8 transform intra:49.1% inter:31.7%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] coded y,uvDC,uvAC intra: 55.0% 53.9% 19.6% inter: 12.1% 12.6% 0.6%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] i16 v,h,dc,p: 39% 28% 23% 10%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 21% 27%  4%  5%  6%  5%  5%  5%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 27% 22% 13%  5%  7%  8%  6%  6%  5%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] i8c dc,h,v,p: 50% 25% 20%  6%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] Weighted P-Frames: Y:0.5% UV:0.1%
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.235] [info]    [ffmpeg] [libx264 @ 0000017BAC98CF80] kb/s:9581.48
[2022-05-15 22:52:50.235] [info]    
[2022-05-15 22:52:50.336] [info]    ffmpeg[ch2/20220515222250.mp4] Uninitialized.
[2022-05-15 23:22:49.062] [info]    Received message from 127.0.0.1: REMOVE 1 FILE ch1/20220515225249.mp4\r\n
[2022-05-15 23:22:49.062] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 23:22:49.062] [info]    ffmpeg[ch1/20220515225249.mp4] Uninitialized.
[2022-05-15 23:22:49.064] [info]    Received message from 127.0.0.1: ADD 1 FILE ch1/20220515232249.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 23:22:49.064] [info]    ffmpeg[ch1/20220515232249.mp4] Initialized.
[2022-05-15 23:22:49.064] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 23:22:49.071] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] using SAR=1/1
[2022-05-15 23:22:49.071] [info]    
[2022-05-15 23:22:49.071] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 23:22:49.071] [info]    
[2022-05-15 23:22:49.083] [info]    [ffmpeg] [libx264 @ 0000017BAC98C680] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 23:22:49.083] [info]    
[2022-05-15 23:22:49.090] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F9300] Pure channel mapping detected:
[2022-05-15 23:22:49.091] [info]    [ffmpeg]  0
[2022-05-15 23:22:49.091] [info]    [ffmpeg]  1
[2022-05-15 23:22:49.091] [info]    [ffmpeg] 
[2022-05-15 23:22:49.091] [info]    
[2022-05-15 23:22:49.094] [warning] ffmpeg[ch1/20220515232249.mp4] Unused option s=1920:1080
[2022-05-15 23:22:49.134] [info]    [ffmpeg] [aac @ 0000017BACD30300] Qavg: 1020.639
[2022-05-15 23:22:49.134] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] frame I:360   Avg QP:24.47  size:110564
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] frame P:22824 Avg QP:12.47  size: 65052
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] frame B:66816 Avg QP:18.29  size:  8843
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] consecutive B-frames:  0.8%  0.7%  0.1% 98.4%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] mb I  I16..4: 50.6% 12.4% 37.0%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] mb P  I16..4:  2.4%  0.9%  0.7%  P16..4: 25.7%  4.0%  4.2%  0.0%  0.0%    skip:62.1%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] mb B  I16..4:  0.2%  0.2%  0.0%  B16..8:  4.1%  1.7%  0.4%  direct: 4.4%  skip:88.8%  L0:37.5% L1:44.0% BI:18.5%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] 8x8 transform intra:24.8% inter:20.4%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] coded y,uvDC,uvAC intra: 59.5% 59.3% 49.4% inter: 8.3% 5.7% 2.6%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] i16 v,h,dc,p: 53% 34%  9%  4%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 21% 26% 32%  3%  2%  2%  4%  4%  5%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 31% 11%  4%  4%  4%  5%  4%  5%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] i8c dc,h,v,p: 42% 30% 23%  5%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] Weighted P-Frames: Y:0.0% UV:0.0%
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.138] [info]    [ffmpeg] [libx264 @ 0000017BF5E4FA00] kb/s:9401.96
[2022-05-15 23:22:49.138] [info]    
[2022-05-15 23:22:49.254] [info]    ffmpeg[ch1/20220515225249.mp4] Uninitialized.
[2022-05-15 23:22:50.105] [info]    Received message from 127.0.0.1: REMOVE 2 FILE ch2/20220515225250.mp4\r\n
[2022-05-15 23:22:50.105] [info]    ffmpeg[ch2/20220515225250.mp4] Uninitialized.
[2022-05-15 23:22:50.105] [info]    Sent message to 127.0.0.1:202 REMOVE OK\r\n
[2022-05-15 23:22:50.108] [info]    Received message from 127.0.0.1: ADD 2 FILE ch2/20220515232250.mp4 -b:v 15000000 -maxrate:v 15000000 -bufsize:v 1000000 -filter:v format=pix_fmts=yuv420p -filter:a pan=stereo|c0=c0|c1=c1 -s 1920:1080\r\n
[2022-05-15 23:22:50.108] [info]    ffmpeg[ch2/20220515232250.mp4] Initialized.
[2022-05-15 23:22:50.108] [info]    Sent message to 127.0.0.1:202 ADD OK\r\n
[2022-05-15 23:22:50.122] [info]    [ffmpeg] [libx264 @ 0000017C5A451940] using SAR=1/1
[2022-05-15 23:22:50.122] [info]    
[2022-05-15 23:22:50.123] [info]    [ffmpeg] [libx264 @ 0000017C5A451940] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2 AVX512
[2022-05-15 23:22:50.123] [info]    
[2022-05-15 23:22:50.127] [info]    [ffmpeg] [libx264 @ 0000017C5A451940] profile High, level 4.2, 4:2:0, 8-bit
[2022-05-15 23:22:50.127] [info]    
[2022-05-15 23:22:50.135] [info]    [ffmpeg] [Parsed_pan_0 @ 0000017BAC9F8200] Pure channel mapping detected:
[2022-05-15 23:22:50.135] [info]    [ffmpeg]  0
[2022-05-15 23:22:50.135] [info]    [ffmpeg]  1
[2022-05-15 23:22:50.135] [info]    [ffmpeg] 
[2022-05-15 23:22:50.135] [info]    
[2022-05-15 23:22:50.136] [warning] ffmpeg[ch2/20220515232250.mp4] Unused option s=1920:1080
[2022-05-15 23:22:50.205] [info]    [ffmpeg] [aac @ 0000017B76EAEDC0] Qavg: 248.886
[2022-05-15 23:22:50.205] [info]    
[2022-05-15 23:22:50.211] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] frame I:424   Avg QP:22.03  size:102237
[2022-05-15 23:22:50.211] [info]    
[2022-05-15 23:22:50.211] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] frame P:23101 Avg QP:18.91  size: 60709
[2022-05-15 23:22:50.211] [info]    
[2022-05-15 23:22:50.211] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] frame B:66474 Avg QP:22.56  size: 10903
[2022-05-15 23:22:50.211] [info]    
[2022-05-15 23:22:50.211] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] consecutive B-frames:  0.8%  1.9%  0.7% 96.6%
[2022-05-15 23:22:50.211] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] mb I  I16..4: 25.7% 45.5% 28.8%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] mb P  I16..4: 12.4% 16.7%  3.0%  P16..4: 30.3% 13.4%  7.6%  0.0%  0.0%    skip:16.6%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] mb B  I16..4:  1.4%  1.2%  0.1%  B16..8: 15.8%  4.5%  0.4%  direct: 9.1%  skip:67.5%  L0:51.0% L1:35.5% BI:13.5%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] 8x8 transform intra:50.4% inter:30.6%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] coded y,uvDC,uvAC intra: 55.4% 42.8% 14.2% inter: 10.7% 9.6% 0.2%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] i16 v,h,dc,p: 44% 27% 20% 10%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 18% 24% 27%  4%  5%  5%  6%  5%  5%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 22% 25% 14%  6%  8%  7%  7%  5%  6%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] i8c dc,h,v,p: 57% 21% 17%  4%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] Weighted P-Frames: Y:0.8% UV:0.3%
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.212] [info]    [ffmpeg] [libx264 @ 0000017BAC98BD40] kb/s:9646.86
[2022-05-15 23:22:50.212] [info]    
[2022-05-15 23:22:50.329] [info]    ffmpeg[ch2/20220515225250.mp4] Uninitialized.
