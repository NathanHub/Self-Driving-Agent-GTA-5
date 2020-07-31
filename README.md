# Self-Driving-Agent-GTA-5
# Author S. Sai Hemanth
# Author Natanael Decena nathannb2424@gmail.com
# e-mail : saihemanth.s@outlook.com
# Author M.L. Vihari
# Author G. RaviTeja

A python program that can drive a car in GTA V

Requirements

1. Vjoy
2. Xbox Vbus for Vjoy (Installaion documentation will be provided in the website)
3. open IV
4. GTA V (Very imortant)
5. Nvidia GTX 1060 and above with a minimum of 6 GB Vram.
6. YOLO v2 weights file https://pjreddie.com/media/files/yolov2.weights download it and put it inside root directory of project
7. Simple trainer for GTA V https://www.gta5-mods.com/scripts/simple-trainer-for-gtav

Python Requirements

1. Python >= 3.5
2. opencv, Installation comman => pip install opencv-python
3. tensorflow GPU, Installation command pip install tensorflow==1.14, pip install tensorflow-gpu==1.14
4. darkFlow "https://github.com/thtrieu/darkflow" Detailed installation procedure is mentioned in this repo.
5. keras
6. Cython
7. shapely
8. pywin32 (Not available via pip directly, Go to https://www.lfd.uci.edu/~gohlke/pythonlibs/ and search for pywin32 and download the compatible wheel, then do pip install xxx.wheel)

Running procedure

Important step

(You have to mod GTA V to change one texture)


open OpenIV and select GTA V for windows and browse for GTA V root folder


![Should be something like this](https://lh3.googleusercontent.com/cKXXSlDx8AHV8-rEAPFtL9u6lL-07tOCWALxM7so3MoMUB5yjGrNedyxe1K1F7e0UXF_C-Rqh2TNHOfQo_f31UzvSqOmPITQ8XAL0ziMrCNjlIskBF3CZKyzZf1-ubfZ9-HLyMFj_0aW-3jCtY2d4IP7GjCu8ij3LiK_0gtwO12IXqE1pAYBYTkn8o1La5UMxpNt0Lq33q_284J9i-8X4_0ZZMIq5sP1ir5BFAh8_6GWDqEERa8qGsLEResnUVI9IDb9y8Ko51GUBFYznU2LbBNUR0vW9Ujmx9xm5-JlU1EeOcSnrNKjj08P-J2pH5GFicGub0uXoa-0XOAfhEIaeL6EJeoa_xQwyY_fRMvm2r0He3QUNMo82UN-rZKz8M3S1oculPmku_JRYZoHRTCqu07tNWp6AZhzanUJJiSKbFUZsJBKztxuHene2iffd8hbM2J11iNrAkDehVGR9xcg8gHGyFfuz12NNkipwMeNZS4wSNi498h6457-rBTR74o1eSV4jNJCYTRRDMEArvc10gfQqAY_0ak_gKKYyB-vODGuZHV8pi2hGwWX4OVVroT_BPvLMQ281ZF51tZbw1NQXk1yAb1kDbODjyZdCvWlBaJs3UaxLNY2iOLJmohsEHivUB72fdvZ6wD0dD1pBU2gOWoDvN4925OUTO7d0UH3coE1ul4hXb_A_w_YF3ab-TxrzjpEnmjhJ_d2k5FqzfsJaQ_TCf1mTPR9AVB0QBx_PTnCcnLy=w640-h692-no)


now select hit "Edit mode" on the top menu then select x64a -> textures -> "right click" on "graphics.ytd" choose "Edit"


![Should be something like this](https://lh3.googleusercontent.com/jCTLR6MK1ijbKziXsA3hxbuPDF7BkuEaTslKa645vO21ruwR8WQXBSQMqxZSf3M2jH3lP4fvlZTrAylYfFNNE1z1ZxyU-d3Yr_TJIRtQAkniN-0ITVziE05Qhddf9Q5653CWKbxfX_lqvx6lIEduK1YUHie_dWEyyBP0_vcSV_Zmh4askmYj2KaF5awnG89gd7M9BRbz5jZDOKaD2PhsHeDH_cvNSmjTbb4PBRAoVTi6Eek3fUrIk-WbhWe61RhrtKJmHo8NYD4QJ6U_KZeDR1Qv4f0pG1nGxGHyYmStvg6u5aad2Oq0lQicUUgXMY_OdfCBAZGMvTZGOQTOJtAagYKH43-YARUC_zxNUp4bNcKwzckkEF8PKJAJN1qWBADw4M1zzL_qiEkKWzAiHPoGyK10wSRx1mv8ZMcVYV7RMg8b-bHiZVy-e89qK6T9gwS8VBGIn17AOm_hQDT3vbqtWM-2WM1ctW5uVVZgaykTaAkUvVRgq5yZqfcMlrKMcnyl0SnO59zgCTA9LCuBZwlMaWO0LUIyDU3_tAaaJQXfm9h8oJLLBA-2PagjGWpXgbVZiX3nvYOLOVqrVeN6ee5Da1wqU1gmO2P0_HSJR8YfH1cRMjbqdOGKS24IuIjZSHif-poblFe8qIsOEb_wpcQL2fv6XmN1XbiKRwusfyble8RLT96HjEohv1wN4Z1CzjcDo7IV4mUXYwnhj2e49r-NExp1RfQwJAIymgiAc1wR86K3zBIn=w800-h500-no)


now a window will open then search for radarmaskm and replace it with the provided one in this repo


![Should be something like this](https://lh3.googleusercontent.com/EV73xZZ7g_TJqEiG8JVZHDOTD2iqaQBrWbEqcX0Upku6dy5E_Yi2Bc9MYPJe73fvK4L_mvbAd1atydm8TgoPq4tfsZRQthV4dddaAluyVnujlWK64TI_LDaCGX4zi_pW5sS6rYXAGSvkLB71f7ias-wtgPWNvYhQDtU5N69xtfcGjluLvsy1xusFj3O7ZUpyjhLBhwJep744_ZHSB1rOdPQDCycHdHzCFQ1xHJ_ganxR_F5ywfMzE8qQBcWI_Fi2ZwAdxh-jLdUx1E3iJwoDhjhqXz8P7l40ruH7PxcsPmGJF8XLoXcqjnnVBox8G5G6WTDzJk-Dxa7q6shDTugyJk52HjhRwcqRMKLTembRTvMaBAARiIbQfx2a3_oDfL0UYH85Umc86bY-4VIy5P5OjmGekZTsVDZs7vXH3mdjPty7oVXj54XQ4AtuTy9-UJZD_bxggR-H0fwFALwqmfesNqKyVKpZ8c0IYIL8cR-w-UwUHbcSWW8jFslpZGrvwWsbY5bECt3Ekbde1wky-jJKXRxRhs7kJi8OVL5ufS9Pg-YIV-FTqEOXbnSdF-jK59LrXBbtnGpFd3hdYTZSsPOrzLhqFYh_s1S4v2lAxntBzPso7tyRsu2xEdJnbi5QaHaIkgxfwPVL68cbLEjxTVXPK3gMKaBMO2KUG1GRNV2c7tM1QZ4uoErUsiIUPv4i2T39H1uQ6BaDVzxjGpVaSrIfP5-cHUxyxqNX_C4BYPyKSCLUQBKt=w600-h338-no)


then close after replacing and in main window hit edit mode again to come out of edit mode and close OpenIV


![Should be something like this](https://lh3.googleusercontent.com/0O4yfTZvQV-kUAjExiPo-pt23I_Rf0Em7QbEDzr4DaE-VyQ6Nw_oADgihqBODsXFI8vu_Lb0hZlqULpB2w6WtWf-F0eD8tfzf7qLxyNoK403oDfA4-W2IIoGLxHjg4OmyL2tGCK1gPjfTd5rhP9YCt4ImBa5y8ufwV0qiEDEzgD7AK3_-n9S-Dpmd6gU-Tuinu8nYcd3jdqycm4ie_bScyTlbo2flzzjyC-DOgeZK5gVv3eYxUCad4N6TUngdLxdcKpwoxGT2iXlK0kfNhXbLOnW1KU2jxXnBDWWGL_PehaoaCRCE8YphiLJTmJ-8P1fP3rTHmhGkgX2oI2vr-3v_euXWMbtv-GFJH3dR1jqb22irtavFZR3izlTUmGI1kRZ5fw7f-8H9aqY-YIe5Z3EodADHhcVy86HVm9GybnzekyyxD51G9akh0Nr7XWoECFRVrWmBz6EpAZ4iaNBxcpYeYz6DNdzXWdWL7MxSCB3oIah5trWQiKbYSP4p6DWBrJ93uYCOxU-aDZXMJR_ymqXdFKFt7opXd8yMkmdO6q-Rv0u0Z3LOp9_23hH56X81kFk1ljwYiQk-mwt8AbSWfiv2FaZ9t1dX5gv2FQd-lciLvKPiekoR-3oNI_qD-LiV942TC62zHYTp3UVRSVoavQA_5i0JpSaJJjn49doMuesuXHI9fYP1Yxzk0u8prU5aScdIVFEndfHEAVDW9hn2PYI41AJIHXKzF96ouLy7ABnA7J8ak_n=w600-h375-no)

then change these settings in GTA V

Resolution = 800 x 600

Mode = windowed

now open digits_collect.py and edit values in vis = image[568:577, 600:699, :]

then make sure that the code outputs image 
![Should be something like this](https://lh3.googleusercontent.com/ru-T2KJn9bIRwtsuMJ3f9PDdCwPUC2HYYsvecD8et8onOpJVInt20ykiyVcjqPPwAROEAzp9RbHSSXw3sOreNGbWHLt2eGwE2A4n_FTmOuCjT9s99KrpAyo9PKn7MRov9e2cK_-Ravem4r8pmjyXKtVE32xQUuq7LYVjSn0idqM9gbfF7wzGwcr_vM62hHEC9xone0q0eI0HaAnljj6q3l7kj0khdBYRmhMRiz0ftNOJja0pAmEc6bKEGqzZ3jY3CXnRrd0uV0czv__HHhbSPwpGeGIGqCjD5VFuWCia2Wrq8DHBlR6kiKDY_a5ohK4lAQUW3l4zogbcsFs_WbXbk1MYme3nlnPj5kRxAOBSgOT-jWX8SKh83HpoulSVtu-APlgpLUFUWGBPQ0__95w19RBKLX94rAI_K_tdHHeiVZxoVE9ED1qbxTL8an5cJ29spb2sELq4Ro1L7hOWiuu3xXkwmWCSTttBY0-HJnGDB4Kvo2kKCIhX9pVISFCdKpZhsLF-QNvDjFIiIDqKXsHnKeL8vqym8y-fzVkkRBnpeoZwqEBgP8MC8zj2pp1eTFo5VntOzW300irJzYw3DYqyLfvfeVNZE74cBewYa0hICfRisxarkOcvsder9emDPQBRi1sIFU46Nsn1YwSh-3OF-G0LhU143rhZb0W4-JQBiBjPyCX7EutrpMZRtjk-315b_TKIXbfc7WZT2n9bcpOQhxaSD4HLRRVXntb5XIxI0tw2VPgC=w1280-h720-no)

make sure that output image dimensions are 8 x 19 (h x w)

now put hese values in img_process.py and put the values in numbers = process(screen[568:576, 681:700, :])
this finishes the setup process for gta v and code

now set a location on the map then the output window should say "press T to start self driving"

<b>Sample output</b> click on the image to see the video.

[![see output here](https://lh3.googleusercontent.com/7CskwLBOBWIy89MjLwRGS8yaluUB4tVp9mEzW9j6VbNHuB2yBaGRIiaFZnUq-2vPMaeXVaMX5jGQnDRPbQYmIEGoUHLwXEnIUdY4jVYMcj7DgVq-LGuOSJIXPgcR2NudvVLDFU-WrUp7aWtjvxuR-IL-vaVLMTpufbSxyI5gcG1Trn4ujKAp59aiubttTgA5vQZ-jcgV0Vi86RRejZ1QmsZMLf_oYiPqXdcBeom3SY9mgo5Bd2ifn7iqjbIcv0Zng2fPgExpuF7YNWNjjTNtRNPYxUxr1Vod3hV2pJhGzd1HZKsI1FoBBNGxD5xILMY_Vxs5tdeun8D4hQv9IgpUBAz_RRg1s01B-AAKIBHAPpa36Eu7g-scV2NGjqEsRR4SzHtqhP3IrKlGqOMV66U_fJOGb8jCuifs1dTWkwVXO_nYENygtT1TWoheSPMXXr6e_Uj4ySlmk5T9eWl86me9DJsiWPpKjBiwEeH20D8WVxPpo86LGZQeU7aKBcTD46HjWTSaTGV-oHuDwfqklkWWYxEC_tpbyCbk0RNeyFkkoyTI0oK9pOL0Rcnxjf-lVFv3TVioFTTRVUIS5of0pAjHsfuL046l66c7WECgwFf-I6rwugYXpLq0lcMt8ILA4cGkoygwJi_SZzG6xfFwXwc5zzr6enEllZa0o2DdgVRkJQvdeu4WHkRumkFcCO_L5aNYh1h2SkkzqJMpAfnU0btveDBA1hiJqiM7mTsnf4h2yHk44HA=w1005-h434-k-no)](https://photos.google.com/share/AF1QipNDiFCXT9rD03iFB44yJylOUiR8C8fkB3DDYZAajSQeRWs2pXThMDHRbaUNyujjxw/photo/AF1QipMwIMAD9i2NYcGR0_N08M4WohsQ4KpatAh42iEt?key=c2FlblJtUVkwbW4zTEVIbWJXWk9rYXlseThRM2FB)



