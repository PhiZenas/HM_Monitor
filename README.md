# HM_Monitor

# The first stage finished at 2015/06/11
# The fowllowing progam is included in the main.cpp

# 1. Download real video from dahua monitor;
# 2. Cut off the dahua frame head and frame end frome every frame;
# 3. Remux the stream form the video soures file rewirited;
# 4. Auto write m3u8 file according to the ts file;
# 5. Adjust every duration of fragment file to 7 seconds;
# 6. The "EXTINF" in m3u8 file is got frome "frame numbers/25";
# 7. Add "EXT-X-VERSION:3" to m3u8 file.

# There is no bug found until now.
# 杭州慧牧科技有限公司HLS监控项目
