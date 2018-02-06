# Setting Up mpc-hc with madVR and SVP

## Downloads

1. [Media Player Classic Homecinema (v1.7.13)](https://mpc-hc.org/downloads/) 32 or 64 bit (either works)
2. [madVR (v0.92.12)](http://madvr.com/)
3. [SVP (4.2.0.122)](https://www.svp-team.com/wiki/Download)
4. [ffdshow tryouts (1.3.4531)](http://ffdshow-tryout.sourceforge.net/download.php)

## Setup

1. Install all of them, then start mpc-hc and set its output to madVR:
   
   ![mpc-hc video output](img/mpc-hc-options-video.png)
   
2. Configure madVR:
   1. Play any file and find the madVR icon in the Notification Area. Right click on it
      and select `Edit madVR Settings...`
   
      ![madVR Notification Area](img/madVR-icon.png)
   
   2. chroma upscaling - Jinc with anti-ringing:
   
      ![Jinc chroma upscaling](img/madVR-chroma.png)
   
   3. image downscaling - Jinc with anti-ringing:
   
      ![Jinc image downscaling](img/madVR-downscaling.png)
   
   4. image upscaling - Jinc (no filters)
   
      ![Jinc image upscaling](img/madVR-upscaling.png)
   
   5. rendering settings:
   
      ![queue sizes](img/madVR-render1.png)

      ![windowed settings](img/madVR-render2.png)

      ![smooth motion](img/madVR-smooth.png)

3. Configure ffdshow raw video filter in mpc-hc:
   
   ![ffdshow raw video filter](img/mpc-hc-ffdshow-raw.png)

4. Test that it works - open any video and notice the ffdshow and the madVR notification area icons
   
   ![notification area](img/notification-area.png)

5. Just start SVP, should notice the SVP logo appear in mpc-hc:
   
   ![SVP logo working](img/svp.png)
