## 支持列表

### ✨图像格式列表

> 详细支持列表 https://ffmpeg.org/general.html#Image-Formats

| 名称                                  | 编码 | 解码 | 注释                                    |
| ------------------------------------- | ---- | ---- | --------------------------------------- |
| .Y.U.V                                | X    | X    | 每个组件一个原始文件                    |
| Alias PIX                             | X    | X    | 别名/ Wavefront PIX图像格式             |
| animated GIF                          | X    | X    |                                         |
| APNG                                  | X    | X    | 动画便携式网络图形                      |
| BMP                                   | X    | X    | Microsoft BMP映像                       |
| BRender PIX                           |      | X    | Argonaut BRender 3D引擎图像格式。       |
| CRI                                   |      | X    | 辛特尔RAW                               |
| DPX                                   | X    | X    | 数码图片交换                            |
| EXR                                   |      | X    | OpenEXR                                 |
| FITS                                  | X    | X    | 灵活的图像传输系统                      |
| JPEG                                  | X    | X    | 不支持渐进JPEG。                        |
| JPEG 2000                             | X    | X    |                                         |
| JPEG-LS                               | X    | X    |                                         |
| LJPEG                                 | X    |      | 无损JPEG                                |
| MSP                                   |      | X    | Microsoft Paint图片                     |
| PAM                                   | X    | X    | PAM是具有alpha支持的PNM扩展。           |
| PBM                                   | X    | X    | 便携式位图图像                          |
| PCD                                   |      | X    | 光盘                                    |
| PCX                                   | X    | X    | PC画笔                                  |
| PFM                                   | X    | X    | 便携式FloatMap图片                      |
| PGM                                   | X    | X    | 便携式GrayMap图片                       |
| PGMYUV                                | X    | X    | 在YUV中具有U和V分量的PGM 4：2：0        |
| PGX                                   |      | X    | PGX文件解码器                           |
| PIC                                   |      | X    | Pictor / PC油漆                         |
| PNG                                   | X    | X    | 便携式网络图形图像                      |
| PPM                                   | X    | X    | 便携式PixelMap图像                      |
| PSD                                   |      | X    | 的Photoshop                             |
| PTX                                   |      | X    | V.Flash PTX格式                         |
| SGI                                   | X    | X    | SGI RGB图像格式                         |
| Sun Rasterfile                        | X    | X    | Sun RAS图像格式                         |
| TIFF                                  | X    | X    | 尚不支持YUV，JPEG和某些扩展名。         |
| Truevision Targa                      | X    | X    | Targa（.TGA）图像格式                   |
| WebP                                  | E    | X    | WebP图像格式，通过外部库libwebp支持编码 |
| XBM                                   | X    | X    | X位图图像格式                           |
| XFace                                 | X    | X    | X-Face图像格式                          |
| XPM                                   |      | X    | X PixMap图像格式                        |
| XWD                                   | X    | X    | X Window Dump图片格式                   |
| X 表示支持该列中的功能（编码/解码）。 |      |      |                                         |
| E 表示通过外部库提供支持。            |      |      |                                         |

### ✨音频格式列表

> 详细支持列表 https://ffmpeg.org/general.html#Audio-Codecs

| 名称                                                         | 编码 | 解码 | 注释                                                  |
| ------------------------------------------------------------ | ---- | ---- | ----------------------------------------------------- |
| 8SVX exponential                                             |      | X    |                                                       |
| 8SVX fibonacci                                               |      | X    |                                                       |
| AAC                                                          | EX   | X    | 通过内部编码器和外部库libfdk-aac支持的编码            |
| AAC+                                                         | E    | IX   | 通过外部库libfdk-aac支持的编码                        |
| AC-3                                                         | IX   | IX   |                                                       |
| ACELP.KELVIN                                                 |      | X    |                                                       |
| ADPCM 4X Movie                                               |      | X    |                                                       |
| ADPCM Yamaha AICA                                            |      | X    |                                                       |
| ADPCM AmuseGraphics Movie                                    |      | X    |                                                       |
| ADPCM Argonaut Games                                         | X    | X    |                                                       |
| ADPCM CDROM XA                                               |      | X    |                                                       |
| ADPCM Creative Technology                                    |      | X    | 16-> 4，8-> 4，8-> 3，8-> 2                           |
| ADPCM Electronic Arts                                        |      | X    | 用于各种EA标题中。                                    |
| ADPCM Electronic Arts Maxis CDROM XS                         |      | X    | 用于Sim City 3000。                                   |
| ADPCM Electronic Arts R1                                     |      | X    |                                                       |
| ADPCM Electronic Arts R2                                     |      | X    |                                                       |
| ADPCM Electronic Arts R3                                     |      | X    |                                                       |
| ADPCM Electronic Arts XAS                                    |      | X    |                                                       |
| ADPCM G.722                                                  | X    | X    |                                                       |
| ADPCM G.726                                                  | X    | X    |                                                       |
| ADPCM IMA AMV                                                | X    | X    | 在AMV文件中使用                                       |
| ADPCM IMA Cunning Developments                               |      | X    |                                                       |
| ADPCM IMA Electronic Arts EACS                               |      | X    |                                                       |
| ADPCM IMA Electronic Arts SEAD                               |      | X    |                                                       |
| ADPCM IMA Funcom                                             |      | X    |                                                       |
| ADPCM IMA High Voltage Software ALP                          | X    | X    |                                                       |
| ADPCM IMA QuickTime                                          | X    | X    |                                                       |
| ADPCM IMA Simon & Schuster  Interactive                      | X    | X    |                                                       |
| ADPCM IMA Ubisoft APM                                        | X    | X    |                                                       |
| ADPCM IMA Loki SDL MJPEG                                     |      | X    |                                                       |
| ADPCM IMA WAV                                                | X    | X    |                                                       |
| ADPCM IMA Westwood                                           |      | X    |                                                       |
| ADPCM ISS IMA                                                |      | X    | 用于FunCom游戏。                                      |
| ADPCM IMA Dialogic                                           |      | X    |                                                       |
| ADPCM IMA Duck DK3                                           |      | X    | 在某些Sega Saturn主机游戏中使用。                     |
| ADPCM IMA Duck DK4                                           |      | X    | 在某些Sega Saturn主机游戏中使用。                     |
| ADPCM IMA Radical                                            |      | X    |                                                       |
| ADPCM Microsoft                                              | X    | X    |                                                       |
| ADPCM MS IMA                                                 | X    | X    |                                                       |
| ADPCM Nintendo Gamecube AFC                                  |      | X    |                                                       |
| ADPCM Nintendo Gamecube DTK                                  |      | X    |                                                       |
| ADPCM Nintendo THP                                           |      | X    |                                                       |
| ADPCM Playstation                                            |      | X    |                                                       |
| ADPCM QT IMA                                                 | X    | X    |                                                       |
| ADPCM SEGA CRI ADX                                           | X    | X    | 在世嘉Dreamcast游戏中使用。                           |
| ADPCM Shockwave Flash                                        | X    | X    |                                                       |
| ADPCM Sound Blaster Pro 2-bit                                |      | X    |                                                       |
| ADPCM Sound Blaster Pro 2.6-bit                              |      | X    |                                                       |
| ADPCM Sound Blaster Pro 4-bit                                |      | X    |                                                       |
| ADPCM VIMA                                                   |      | X    | 用于LucasArts SMUSH动画中。                           |
| ADPCM Westwood Studios IMA                                   | X    | X    | 用于Westwood Studios游戏中，例如Command和Conquer。    |
| ADPCM Yamaha                                                 | X    | X    |                                                       |
| ADPCM Zork                                                   |      | X    |                                                       |
| AMR-NB                                                       | E    | X    | 通过外部库libopencore-amrnb支持的编码                 |
| AMR-WB                                                       | E    | X    | 通过外部库libvo-amrwbenc支持的编码                    |
| Amazing Studio PAF Audio                                     |      | X    |                                                       |
| Apple lossless audio                                         | X    | X    | QuickTime fourcc'alac'                                |
| aptX                                                         | X    | X    | 用于蓝牙A2DP                                          |
| aptX HD                                                      | X    | X    | 用于蓝牙A2DP                                          |
| ATRAC1                                                       |      | X    |                                                       |
| ATRAC3                                                       |      | X    |                                                       |
| ATRAC3+                                                      |      | X    |                                                       |
| ATRAC9                                                       |      | X    |                                                       |
| Bink Audio                                                   |      | X    | 在许多游戏中用在Bink和Smacker文件中。                 |
| CELT                                                         |      | E    | 通过外部库libcelt支持解码                             |
| codec2                                                       | E    | E    | 通过外部库libcodec2支持en / decoding                  |
| CRI HCA                                                      |      | X    |                                                       |
| Delphine Software International CIN audio                    |      | X    | Delphine Software International游戏中使用的编解码器。 |
| Digital Speech Standard - Standard Play  mode (DSS SP)       |      | X    |                                                       |
| Discworld II BMV Audio                                       |      | X    |                                                       |
| COOK                                                         |      | X    | 支持除5.1之外的所有版本。                             |
| DCA (DTS Coherent Acoustics)                                 | X    | X    | 支持的扩展名：XCh，XXCH，X96，XBR，XLL，LBR（部分）   |
| Dolby E                                                      |      | X    |                                                       |
| DPCM Gremlin                                                 |      | X    |                                                       |
| DPCM id RoQ                                                  | X    | X    | 用于Quake III，Jedi Knight 2和其他计算机游戏。        |
| DPCM Interplay                                               |      | X    | 用于各种Interplay电脑游戏。                           |
| DPCM Squareroot-Delta-Exact                                  |      | X    | 用于各种游戏。                                        |
| DPCM Sierra Online                                           |      | X    | 用于Sierra Online游戏音频文件。                       |
| DPCM Sol                                                     |      | X    |                                                       |
| DPCM Xan                                                     |      | X    | 在Origin的Wing Commander IV AVI文件中使用。           |
| DPCM Xilam DERF                                              |      | X    |                                                       |
| DSD (Direct Stream Digital), least  significant bit first    |      | X    |                                                       |
| DSD (Direct Stream Digital), most  significant bit first     |      | X    |                                                       |
| DSD (Direct Stream Digital), least  significant bit first, planar |      | X    |                                                       |
| DSD (Direct Stream Digital), most  significant bit first, planar |      | X    |                                                       |
| DSP Group TrueSpeech                                         |      | X    |                                                       |
| DST (Direct Stream Transfer)                                 |      | X    |                                                       |
| DV audio                                                     |      | X    |                                                       |
| Enhanced AC-3                                                | X    | X    |                                                       |
| EVRC (Enhanced Variable Rate Codec)                          |      | X    |                                                       |
| FLAC (Free Lossless Audio Codec)                             | X    | IX   |                                                       |
| G.723.1                                                      | X    | X    |                                                       |
| G.729                                                        |      | X    |                                                       |
| GSM                                                          | E    | X    | 通过外部库libgsm支持的编码                            |
| GSM Microsoft variant                                        | E    | X    | 通过外部库libgsm支持的编码                            |
| IAC (Indeo Audio Coder)                                      |      | X    |                                                       |
| iLBC (Internet Low Bitrate Codec)                            | E    | E    | 通过外部库libilbc支持的编码和解码                     |
| IMC (Intel Music Coder)                                      |      | X    |                                                       |
| Interplay ACM                                                |      | X    |                                                       |
| MACE (Macintosh Audio  Compression/Expansion) 3:1            |      | X    |                                                       |
| MACE (Macintosh Audio  Compression/Expansion) 6:1            |      | X    |                                                       |
| MLP (Meridian Lossless Packing)                              | X    | X    | 用于DVD音频光盘。                                     |
| Monkey’s Audio                                               |      | X    |                                                       |
| MP1 (MPEG audio layer 1)                                     |      | IX   |                                                       |
| MP2 (MPEG audio layer 2)                                     | IX   | IX   | 外部库TwoLAME也支持编码                               |
| MP3 (MPEG audio layer 3)                                     | E    | IX   | 通过外部库LAME，ADU MP3和MP3onMP4支持的编码           |
| MPEG-4 Audio Lossless Coding (ALS)                           |      | X    |                                                       |
| Musepack SV7                                                 |      | X    |                                                       |
| Musepack SV8                                                 |      | X    |                                                       |
| Nellymoser Asao                                              | X    | X    |                                                       |
| On2 AVC (Audio for Video Codec)                              |      | X    |                                                       |
| Opus                                                         | E    | X    | 通过外部库libopus支持编码                             |
| PCM A-law                                                    | X    | X    |                                                       |
| PCM mu-law                                                   | X    | X    |                                                       |
| PCM Archimedes VIDC                                          | X    | X    |                                                       |
| PCM signed 8-bit planar                                      | X    | X    |                                                       |
| PCM signed 16-bit big-endian planar                          | X    | X    |                                                       |
| PCM signed 16-bit little-endian planar                       | X    | X    |                                                       |
| PCM signed 24-bit little-endian planar                       | X    | X    |                                                       |
| PCM signed 32-bit little-endian planar                       | X    | X    |                                                       |
| PCM 32-bit floating point big-endian                         | X    | X    |                                                       |
| PCM 32-bit floating point little-endian                      | X    | X    |                                                       |
| PCM 64-bit floating point big-endian                         | X    | X    |                                                       |
| PCM 64-bit floating point little-endian                      | X    | X    |                                                       |
| PCM D-Cinema audio signed 24-bit                             | X    | X    |                                                       |
| PCM signed 8-bit                                             | X    | X    |                                                       |
| PCM signed 16-bit big-endian                                 | X    | X    |                                                       |
| PCM signed 16-bit little-endian                              | X    | X    |                                                       |
| PCM signed 24-bit big-endian                                 | X    | X    |                                                       |
| PCM signed 24-bit little-endian                              | X    | X    |                                                       |
| PCM signed 32-bit big-endian                                 | X    | X    |                                                       |
| PCM signed 32-bit little-endian                              | X    | X    |                                                       |
| PCM signed 16/20/24-bit big-endian in  MPEG-TS               |      | X    |                                                       |
| PCM unsigned 8-bit                                           | X    | X    |                                                       |
| PCM unsigned 16-bit big-endian                               | X    | X    |                                                       |
| PCM unsigned 16-bit little-endian                            | X    | X    |                                                       |
| PCM unsigned 24-bit big-endian                               | X    | X    |                                                       |
| PCM unsigned 24-bit little-endian                            | X    | X    |                                                       |
| PCM unsigned 32-bit big-endian                               | X    | X    |                                                       |
| PCM unsigned 32-bit little-endian                            | X    | X    |                                                       |
| QCELP / PureVoice                                            |      | X    |                                                       |
| QDesign Music Codec 1                                        |      | X    |                                                       |
| QDesign Music Codec 2                                        |      | X    | 仍然存在一些失真。                                    |
| RealAudio 1.0 (14.4K)                                        | X    | X    | 实际14400 bit / s编解码器                             |
| RealAudio 2.0 (28.8K)                                        |      | X    | 实数28800 bit / s编解码器                             |
| RealAudio 3.0 (dnet)                                         | IX   | X    | 真正的低比特率AC-3编解码器                            |
| RealAudio Lossless                                           |      | X    |                                                       |
| RealAudio SIPR / ACELP.NET                                   |      | X    |                                                       |
| SBC (low-complexity subband codec)                           | X    | X    | 用于蓝牙A2DP                                          |
| Shorten                                                      |      | X    |                                                       |
| Sierra VMD audio                                             |      | X    | 在Sierra VMD文件中使用。                              |
| Smacker audio                                                |      | X    |                                                       |
| SMPTE 302M AES3 audio                                        | X    | X    |                                                       |
| Sonic                                                        | X    | X    | 实验编解码器                                          |
| Sonic lossless                                               | X    | X    | 实验编解码器                                          |
| Speex                                                        | E    | E    | 通过外部库libspeex支持                                |
| TAK (Tom’s lossless Audio Kompressor)                        |      | X    |                                                       |
| True Audio (TTA)                                             | X    | X    |                                                       |
| TrueHD                                                       | X    | X    | 用于HD-DVD和Blu-Ray光盘。                             |
| TwinVQ (VQF flavor)                                          |      | X    |                                                       |
| VIMA                                                         |      | X    | 用于LucasArts SMUSH动画中。                           |
| Vorbis                                                       | E    | X    | 存在本机但非常原始的编码器。                          |
| Voxware MetaSound                                            |      | X    |                                                       |
| WavPack                                                      | X    | X    |                                                       |
| Westwood Audio (SND1)                                        |      | X    |                                                       |
| Windows Media Audio 1                                        | X    | X    |                                                       |
| Windows Media Audio 2                                        | X    | X    |                                                       |
| Windows Media Audio Lossless                                 |      | X    |                                                       |
| Windows Media Audio Pro                                      |      | X    |                                                       |
| Windows Media Audio Voice                                    |      | X    |                                                       |
| Xbox Media Audio 1                                           |      | X    |                                                       |
| Xbox Media Audio 2                                           |      | X    |                                                       |
| X 表示支持该列中的功能（编码/解码）。                        |      |      |                                                       |
| E 表示通过外部库提供支持。                                   |      |      |                                                       |
| I 意味着也只有整数版本可用（确保在不支持硬件浮点的系统上具有高性能）。 |      |      |                                                       |

### ✨视频格式列表

> 详细支持列表 https://ffmpeg.org/general.html#Video-Codecs

| 名称                                                     | 编码 | 解码 | 注释                                                  |
| -------------------------------------------------------- | ---- | ---- | ----------------------------------------------------- |
| 4X Movie                                                 |      | X    | 用于某些计算机游戏。                                  |
| 8088flex TMV                                             |      | X    |                                                       |
| A64 multicolor                                           | X    |      | 创建适合在准将64（多色模式）上播放的视频。            |
| Amazing Studio PAF Video                                 |      | X    |                                                       |
| American Laser Games MM                                  |      | X    | 用于Mad Dog McCree等游戏。                            |
| Amuse Graphics Movie                                     |      | X    |                                                       |
| AMV Video                                                | X    | X    | 用于中国MP3播放器。                                   |
| ANSI/ASCII art                                           |      | X    |                                                       |
| Apple Intermediate Codec                                 |      | X    |                                                       |
| Apple MJPEG-B                                            |      | X    |                                                       |
| Apple Pixlet                                             |      | X    |                                                       |
| Apple ProRes                                             | X    | X    | fourcc：apch，apcn，apcs，apco，ap4h，ap4x            |
| Apple QuickDraw                                          |      | X    | fourcc：qdrw                                          |
| Argonaut Video                                           |      | X    | 在某些Argonaut游戏中使用。                            |
| Asus v1                                                  | X    | X    | fourcc：ASV1                                          |
| Asus v2                                                  | X    | X    | fourcc：ASV2                                          |
| ATI VCR1                                                 |      | X    | fourcc：VCR1                                          |
| ATI VCR2                                                 |      | X    | fourcc：VCR2                                          |
| Auravision Aura                                          |      | X    |                                                       |
| Auravision Aura 2                                        |      | X    |                                                       |
| Autodesk Animator Flic video                             |      | X    |                                                       |
| Autodesk RLE                                             |      | X    | fourcc：AASC                                          |
| AV1                                                      | E    | E    | 通过外部库libaom，libdav1d，librav1e和libsvtav1支持   |
| Avid 1:1 10-bit RGB Packer                               | X    | X    | fourcc：AVrp                                          |
| AVS (Audio Video Standard) video                         |      | X    | Creature Creature游戏使用的视频编码。                 |
| AVS2-P2/IEEE1857.4                                       | E    | E    | 通过外部库libxavs2和libdavs2支持                      |
| AVS3-P2/IEEE1857.10                                      |      | E    | 通过外部库libuavs3d支持                               |
| AYUV                                                     | X    | X    | Microsoft未压缩的打包4：4：4：4                       |
| Beam Software VB                                         |      | X    |                                                       |
| Bethesda VID video                                       |      | X    | 在Bethesda Softworks的某些游戏中使用。                |
| Bink Video                                               |      | X    |                                                       |
| BitJazz SheerVideo                                       |      | X    |                                                       |
| Bitmap Brothers JV video                                 |      | X    |                                                       |
| y41p Brooktree uncompressed 4:1:1 12-bit                 | X    | X    |                                                       |
| Brooktree ProSumer Video                                 |      | X    | fourcc：BT20                                          |
| Brute Force & Ignorance                                  |      | X    | 用于游戏Flash Traffic：天使之城。                     |
| C93 video                                                |      | X    | Cyberia游戏中使用的编解码器。                         |
| CamStudio                                                |      | X    | fourcc：CSCD                                          |
| CD+G                                                     |      | X    | CD + G卡拉OK光盘的视频编解码器                        |
| CDXL                                                     |      | X    | Amiga CD视频编解码器                                  |
| Chinese AVS video                                        | E    | X    | AVS1-P2，JiZhun概要文件，通过外部库libxavs进行编码    |
| Delphine Software International CIN video                |      | X    | Delphine Software International游戏中使用的编解码器。 |
| Discworld II BMV Video                                   |      | X    |                                                       |
| CineForm HD                                              | X    | X    |                                                       |
| Canopus HQ                                               |      | X    |                                                       |
| Canopus HQA                                              |      | X    |                                                       |
| Canopus HQX                                              |      | X    |                                                       |
| Canopus Lossless Codec                                   |      | X    |                                                       |
| CDToons                                                  |      | X    | 在各种Broderbund游戏中使用的编解码器。                |
| Cinepak                                                  |      | X    |                                                       |
| Cirrus Logic AccuPak                                     | X    | X    | fourcc：CLJR                                          |
| CPiA Video Format                                        |      | X    |                                                       |
| Creative YUV (CYUV)                                      |      | X    |                                                       |
| DFA                                                      |      | X    | Chronomaster游戏中使用的编解码器。                    |
| Dirac                                                    | E    | X    | 通过本地vc2（Dirac Pro）编码器支持                    |
| Deluxe Paint Animation                                   |      | X    |                                                       |
| DNxHD                                                    | X    | X    | 又名SMPTE VC3                                         |
| Duck TrueMotion 1.0                                      |      | X    | fourcc：duck                                          |
| Duck TrueMotion 2.0                                      |      | X    | fourcc：TM20                                          |
| Duck TrueMotion 2.0 RT                                   |      | X    | fourcc：TR20                                          |
| DV (Digital Video)                                       | X    | X    |                                                       |
| Dxtory capture format                                    |      | X    |                                                       |
| Feeble Files/ScummVM DXA                                 |      | X    | 最初在Feeble Files游戏中使用的编解码器。              |
| Electronic Arts CMV video                                |      | X    | 用于NHL 95游戏。                                      |
| Electronic Arts Madcow video                             |      | X    |                                                       |
| Electronic Arts TGV video                                |      | X    |                                                       |
| Electronic Arts TGQ video                                |      | X    |                                                       |
| Electronic Arts TQI video                                |      | X    |                                                       |
| Escape 124                                               |      | X    |                                                       |
| Escape 130                                               |      | X    |                                                       |
| FFmpeg video codec #1                                    | X    | X    | 无损编解码器（fourcc：FFV1）                          |
| Flash Screen Video v1                                    | X    | X    | fourcc：FSV1                                          |
| Flash Screen Video v2                                    | X    | X    |                                                       |
| Flash Video (FLV)                                        | X    | X    | 闪存中使用的Sorenson H.263                            |
| FM Screen Capture Codec                                  |      | X    |                                                       |
| Forward Uncompressed                                     |      | X    |                                                       |
| Fraps                                                    |      | X    |                                                       |
| Go2Meeting                                               |      | X    | fourcc：G2M2，G2M3                                    |
| Go2Webinar                                               |      | X    | fourcc：G2M4                                          |
| Gremlin Digital Video                                    |      | X    |                                                       |
| H.261                                                    | X    | X    |                                                       |
| H.263 / H.263-1996                                       | X    | X    |                                                       |
| H.263+ / H.263-1998 / H.263 version 2                    | X    | X    |                                                       |
| H.264 / AVC / MPEG-4 AVC / MPEG-4 part 10                | E    | X    | 通过外部库libx264和OpenH264支持的编码                 |
| HEVC                                                     | X    | X    | 通过外部库libx265和libkvazaar支持的编码               |
| HNM version 4                                            |      | X    |                                                       |
| HuffYUV                                                  | X    | X    |                                                       |
| HuffYUV FFmpeg variant                                   | X    | X    |                                                       |
| IBM Ultimotion                                           |      | X    | fourcc：ULTI                                          |
| id Cinematic video                                       |      | X    | 在雷神之锤II中使用。                                  |
| id RoQ video                                             | X    | X    | 用于Quake III，Jedi Knight 2和其他计算机游戏。        |
| IFF ILBM                                                 |      | X    | IFF交错位图                                           |
| IFF ByteRun1                                             |      | X    | IFF游程长度编码位图                                   |
| Infinity IMM4                                            |      | X    |                                                       |
| Intel H.263                                              |      | X    |                                                       |
| Intel Indeo 2                                            |      | X    |                                                       |
| Intel Indeo 3                                            |      | X    |                                                       |
| Intel Indeo 4                                            |      | X    |                                                       |
| Intel Indeo 5                                            |      | X    |                                                       |
| Interplay C93                                            |      | X    | 在Interplay游戏《赛伯亚》中使用。                     |
| Interplay MVE video                                      |      | X    | 在Interplay .MVE文件中使用。                          |
| J2K                                                      | X    | X    |                                                       |
| Karl Morton’s video codec                                |      | X    | Worms游戏中使用的编解码器。                           |
| Kega Game Video (KGV1)                                   |      | X    | Kega仿真器屏幕捕获编解码器。                          |
| Lagarith                                                 |      | X    |                                                       |
| LCL (LossLess Codec Library) MSZH                        |      | X    |                                                       |
| LCL (LossLess Codec Library) ZLIB                        | E    | E    |                                                       |
| LOCO                                                     |      | X    |                                                       |
| LucasArts SANM/Smush                                     |      | X    | 用于LucasArts游戏/ SMUSH动画中。                      |
| lossless MJPEG                                           | X    | X    |                                                       |
| MagicYUV Video                                           | X    | X    |                                                       |
| Mandsoft Screen Capture Codec                            |      | X    |                                                       |
| Microsoft ATC Screen                                     |      | X    | 也称为Microsoft Screen 3。                            |
| Microsoft Expression Encoder Screen                      |      | X    | 也称为Microsoft Titanium Screen 2。                   |
| Microsoft RLE                                            |      | X    |                                                       |
| Microsoft Screen 1                                       |      | X    | 也称为Windows Media Video V7屏幕。                    |
| Microsoft Screen 2                                       |      | X    | 也称为Windows Media Video V9屏幕。                    |
| Microsoft Video 1                                        |      | X    |                                                       |
| Mimic                                                    |      | X    | 在MSN Messenger网络摄像头流中使用。                   |
| Miro VideoXL                                             |      | X    | fourcc：VIXL                                          |
| MJPEG (Motion JPEG)                                      | X    | X    |                                                       |
| Mobotix MxPEG video                                      |      | X    |                                                       |
| Motion Pixels video                                      |      | X    |                                                       |
| MPEG-1 video                                             | X    | X    |                                                       |
| MPEG-2 video                                             | X    | X    |                                                       |
| MPEG-4 part 2                                            | X    | X    | libxvidcore可以替代地用于编码。                       |
| MPEG-4 part 2 Microsoft variant version 1                |      | X    |                                                       |
| MPEG-4 part 2 Microsoft variant version 2                | X    | X    |                                                       |
| MPEG-4 part 2 Microsoft variant version 3                | X    | X    |                                                       |
| Newtek SpeedHQ                                           | X    | X    |                                                       |
| Nintendo Gamecube THP video                              |      | X    |                                                       |
| NotchLC                                                  |      | X    |                                                       |
| NuppelVideo/RTjpeg                                       |      | X    | NuppelVideo文件中使用的视频编码。                     |
| On2 VP3                                                  |      | X    | 仍处于实验阶段                                        |
| On2 VP4                                                  |      | X    | fourcc：VP40                                          |
| On2 VP5                                                  |      | X    | fourcc：VP50                                          |
| On2 VP6                                                  |      | X    | fourcc：VP60，VP61，VP62                              |
| On2 VP7                                                  |      | X    | fourcc：VP70，VP71                                    |
| VP8                                                      | E    | X    | fourcc：VP80，通过外部库libvpx支持编码                |
| VP9                                                      | E    | X    | 通过外部库libvpx支持的编码                            |
| Pinnacle TARGA CineWave YUV16                            |      | X    | fourcc：Y216                                          |
| Q-team QPEG                                              |      | X    | fourccs：QPEG，Q1.0，Q1.1                             |
| QuickTime 8BPS video                                     |      | X    |                                                       |
| QuickTime Animation (RLE) video                          | X    | X    | fourcc：“ rle”                                        |
| QuickTime Graphics (SMC)                                 |      | X    | fourcc：“ smc”                                        |
| QuickTime video (RPZA)                                   | X    | X    | fourcc：rpza                                          |
| R10K AJA Kona 10-bit RGB Codec                           | X    | X    |                                                       |
| R210 Quicktime Uncompressed RGB 10-bit                   | X    | X    |                                                       |
| Raw Video                                                | X    | X    |                                                       |
| RealVideo 1.0                                            | X    | X    |                                                       |
| RealVideo 2.0                                            | X    | X    |                                                       |
| RealVideo 3.0                                            |      | X    | 距离理想还差得远                                      |
| RealVideo 4.0                                            |      | X    |                                                       |
| Renderware TXD (TeXture Dictionary)                      |      | X    | Renderware Engine使用的纹理字典。                     |
| RL2 video                                                |      | X    | 由娱乐软件合作伙伴在某些游戏中使用                    |
| ScreenPressor                                            |      | X    |                                                       |
| Screenpresso                                             |      | X    |                                                       |
| Screen Recorder Gold Codec                               |      | X    |                                                       |
| Sierra VMD video                                         |      | X    | 在Sierra VMD文件中使用。                              |
| Silicon Graphics Motion Video Compressor  1 (MVC1)       |      | X    |                                                       |
| Silicon Graphics Motion Video Compressor  2 (MVC2)       |      | X    |                                                       |
| Silicon Graphics RLE 8-bit video                         |      | X    |                                                       |
| Smacker video                                            |      | X    | Smacker中使用的视频编码。                             |
| SMPTE VC-1                                               |      | X    |                                                       |
| Snow                                                     | X    | X    | 实验小波编解码器（fourcc：SNOW）                      |
| Sony PlayStation MDEC (Motion DECoder)                   |      | X    |                                                       |
| Sorenson Vector Quantizer 1                              | X    | X    | fourcc：SVQ1                                          |
| Sorenson Vector Quantizer 3                              |      | X    | fourcc：SVQ3                                          |
| Sunplus JPEG (SP5X)                                      |      | X    | fourcc：SP5X                                          |
| TechSmith Screen Capture Codec                           |      | X    | fourcc：TSCC                                          |
| TechSmith Screen Capture Codec 2                         |      | X    | fourcc：TSC2                                          |
| Theora                                                   | E    | X    | 通过外部库libtheora支持的编码                         |
| Tiertex Limited SEQ video                                |      | X    | 在DOS CD-ROM FlashBack游戏中使用的编解码器。          |
| Ut Video                                                 | X    | X    |                                                       |
| v210 QuickTime uncompressed 4:2:2 10-bit                 | X    | X    |                                                       |
| v308 QuickTime uncompressed 4:4:4                        | X    | X    |                                                       |
| v408 QuickTime uncompressed 4:4:4:4                      | X    | X    |                                                       |
| v410 QuickTime uncompressed 4:4:4 10-bit                 | X    | X    |                                                       |
| VBLE Lossless Codec                                      |      | X    |                                                       |
| VMware Screen Codec / VMware Video                       |      | X    | VMware捕获的视频中使用的编解码器。                    |
| Westwood Studios VQA (Vector Quantized  Animation) video |      | X    |                                                       |
| Windows Media Image                                      |      | X    |                                                       |
| Windows Media Video 7                                    | X    | X    |                                                       |
| Windows Media Video 8                                    | X    | X    |                                                       |
| Windows Media Video 9                                    |      | X    | 不能完全正常工作                                      |
| Wing Commander III / Xan                                 |      | X    | 在Wing Commander III .MVE文件中使用。                 |
| Wing Commander IV / Xan                                  |      | X    | 在Wing Commander IV中使用。                           |
| Winnov WNV1                                              |      | X    |                                                       |
| WMV7                                                     | X    | X    |                                                       |
| YAMAHA SMAF                                              | X    | X    |                                                       |
| Psygnosis YOP Video                                      |      | X    |                                                       |
| yuv4                                                     | X    | X    | libquicktime未压缩打包4：2：0                         |
| ZeroCodec Lossless Video                                 |      | X    |                                                       |
| ZLIB                                                     | X    | X    | LCL的一部分，编码器实验性                             |
| Zip Motion Blocks Video                                  | X    | X    | 编码器仅在PAL8中工作。                                |
| X 表示支持该列中的功能（编码/解码）。                    |      |      |                                                       |
| E 表示通过外部库提供支持。                               |      |      |                                                       |

### ✨字幕格式列表

> 详细支持列表 https://ffmpeg.org/general.html#Subtitle-Formats

| 名称                                  | 多路复用技术 | 多路分配器 | 编码 | 解码 |
| ------------------------------------- | ------------ | ---------- | ---- | ---- |
| 3GPP Timed Text                       |              |            | X    | X    |
| AQTitle                               |              | X          |      | X    |
| DVB                                   | X            | X          | X    | X    |
| DVB teletext                          |              | X          |      | E    |
| DVD                                   | X            | X          | X    | X    |
| JACOsub                               | X            | X          |      | X    |
| MicroDVD                              | X            | X          |      | X    |
| MPL2                                  |              | X          |      | X    |
| MPsub (MPlayer)                       |              | X          |      | X    |
| PGS                                   |              |            |      | X    |
| PJS (Phoenix)                         |              | X          |      | X    |
| RealText                              |              | X          |      | X    |
| SAMI                                  |              | X          |      | X    |
| Spruce format (STL)                   |              | X          |      | X    |
| SSA/ASS                               | X            | X          | X    | X    |
| SubRip (SRT)                          | X            | X          | X    | X    |
| SubViewer v1                          |              | X          |      | X    |
| SubViewer                             |              | X          |      | X    |
| TED Talks captions                    |              | X          |      | X    |
| TTML                                  | X            |            | X    |      |
| VobSub (IDX+SUB)                      |              | X          |      | X    |
| VPlayer                               |              | X          |      | X    |
| WebVTT                                | X            | X          | X    | X    |
| XSUB                                  |              |            | X    | X    |
| X 表示支持该列中的功能（编码/解码）。 |              |            |      |      |
| E 表示通过外部库提供支持。            |              |            |      |      |

### ✨[网络协议列表]()

> 详细支持列表 https://ffmpeg.org/general.html#Network-Protocols

| 名称                                  | 支持 |
| ------------------------------------- | ---- |
| AMQP                                  | E    |
| file                                  | X    |
| FTP                                   | X    |
| Gopher                                | X    |
| Gophers                               | X    |
| HLS                                   | X    |
| HTTP                                  | X    |
| HTTPS                                 | X    |
| Icecast                               | X    |
| MMSH                                  | X    |
| MMST                                  | X    |
| pipe                                  | X    |
| Pro-MPEG FEC                          | X    |
| RTMP                                  | X    |
| RTMPE                                 | X    |
| RTMPS                                 | X    |
| RTMPT                                 | X    |
| RTMPTE                                | X    |
| RTMPTS                                | X    |
| RTP                                   | X    |
| SAMBA                                 | E    |
| SCTP                                  | X    |
| SFTP                                  | E    |
| TCP                                   | X    |
| TLS                                   | X    |
| UDP                                   | X    |
| ZMQ                                   | E    |
| X 表示支持该列中的功能（编码/解码）。 |      |
| E 表示通过外部库提供支持。            |      |