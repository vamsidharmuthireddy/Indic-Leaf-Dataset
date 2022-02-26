# Indic-Leaf-Dataset

This dataset is used in the paper, "Indian Plant Recognition in the Wild". You can read the specifics of the dataset in the following link.

Paper link: http://cvit.iiit.ac.in/images/ConferencePapers/2019/Recognition_Wild_ncvpripg19.pdf



If you want to download a tar.gz file: [Link-1](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/vamsidhar_muthireddy_research_iiit_ac_in/EdWRJ3vxoCNBrse8oz2p_VwBMTrDL60sJgi4g7yCIq4OJg)



**Dataset Structure**

The structure of the dataset is as follows.


```
📂 Class Name
 ┣ 📂 Level-0
 ┣ 📂 Level-1
 ┣ 📂 Level-2
 ┣ 📂 Level-3
 ┣ 📂 Level-web
 
```

 1. **📂Level-0** contains scan-like images of our dataset.
 2. **📂Level-1** contains images that capture a single leaf in its entirety so that the visibility of the blade area is maximized.
 3. **📂Level-2** contains images that capture details of a leaf cluster; the arrangement of the leaves along a stem/branch
 4. **📂Level-3** contains images capturing partial/full view of the plant/tree.
 5. **📂Level-web** contains images that we collected from various online sources.



 | Species | Class Name | Level-0 | Level-1 | Level-2 | Level-3 | Level-web | Total | 
 |  ---  |  ---  |  ---  |  ---  |  ---  |  ---  |  ---  |  --- 
 | Jackfruit | 1_jackfruit | 19 | 54 | 50 | 47 | 58 | 228 | 
 | Kadamba | 2_kadamba | 31 | 86 | 53 | 57 | 106 | 333 | 
 | Kanchanara | 3_kanchanara | 30 | 48 | 60 | 49 | 102 | 289 | 
 | Spanishcherry | 4_spanish_cherry | 22 | 48 | 49 | 61 | 123 | 303 | 
 | Plumeria | 5_plumeria | 30 | 98 | 53 | 52 | 93 | 326 | 
 | Euphorbia | 6_euphorbia | 30 | 104 | 51 | 51 | 112 | 348 | 
 | Periwinkle | 7_periwinkle | 40 | 58 | 83 | 44 | 116 | 341 | 
 | Indianrhubarb | 8_indian_rhubarb | 0 | 31 | 0 | 0 | 119 | 150 | 
 | Mandaram | 9_mandaram | 31 | 84 | 53 | 18 | 57 | 243 | 
 | Rose | 10_rose | 0 | 30 | 0 | 0 | 49 | 79 | 
 | Custard apple | 11_custard_apple | 30 | 59 | 50 | 55 | 72 | 266 | 
 | Sausage tree | 12_sausage_tree | 36 | 103 | 101 | 49 | 91 | 380 | 
 | Karanda | 13_karanda | 46 | 103 | 105 | 59 | 112 | 425 | 
 | Jasmine crape | 14_jasmine_crape | 26 | 51 | 51 | 58 | 52 | 238 | 
 | Ashokachettu | 15_ashokachettu | 31 | 48 | 93 | 58 | 128 | 358 | 
 | Sapota | 16_sapota | 31 | 50 | 51 | 69 | 128 | 329 | 
 | Lemon | 17_lemon | 30 | 50 | 50 | 50 | 77 | 257 | 
 | Mosambe | 18_mosambe | 30 | 50 | 54 | 60 | 79 | 273 | 
 | Gauva | 19_gauva | 32 | 55 | 50 | 69 | 66 | 272 | 
 | Kanakambaram | 20_kanakambaram | 30 | 51 | 51 | 30 | 66 | 228 | 
 | Marigold | 21_marigold | 30 | 0 | 54 | 51 | 29 | 164 | 
 | Tamarind | 22_tamarind | 31 | 49 | 62 | 56 | 109 | 307 | 
 | Pomegranate | 23_pomegranate | 31 | 37 | 50 | 55 | 54 | 227 | 
 | Repalachettu | 24_repalachettu | 31 | 53 | 50 | 36 | 50 | 220 | 
 | Gliricidia | 25_gliricidia | 31 | 51 | 53 | 51 | 81 | 267 | 
 | Drumstick | 26_drumstick | 31 | 30 | 50 | 49 | 74 | 234 | 
 | Gandham | 27_gandham | 30 | 54 | 50 | 50 | 75 | 259 | 
 | Cashew | 28_cashew | 30 | 50 | 50 | 55 | 102 | 287 | 
 | Plumbago | 29_plumbago | 25 | 65 | 73 | 64 | 51 | 278 | 
 | Boxwood | 30_boxwood | 30 | 51 | 53 | 59 | 147 | 340 | 
 | Ixora orange | 31_ixora_orange | 47 | 50 | 46 | 51 | 19 | 213 | 
 | Ixora bright pink | 32_ixora_bright_pink | 50 | 46 | 50 | 30 | 13 | 189 | 
 | Ixora dark pink | 33_ixora_dark_pink | 30 | 50 | 52 | 35 | 25 | 192 | 
 | Ixora scarlet | 34_ixora_scarlet | 27 | 50 | 33 | 33 | 28 | 171 | 
 | Arrow head | 35_arrow_head | 31 | 50 | 40 | 53 | 148 | 322 | 
 | Cape honey suckle | 36_cape_honey_suckle | 30 | 52 | 48 | 46 | 100 | 276 | 
 | Jasmine Pinwheel | 37_jasmine_pinwheel | 35 | 50 | 53 | 50 | 77 | 265 | 
 | Gold Dust | 38_gold_dust | 30 | 53 | 48 | 44 | 173 | 348 | 
 | Peacock tail | 39_peacock_tail | 30 | 0 | 48 | 36 | 122 | 236 | 
 | Neem | 40_neem | 31 | 54 | 54 | 50 | 140 | 329 | 
 | Mango | 41_mango | 34 | 50 | 51 | 51 | 100 | 286 | 
 | Acalypa | 42_acalypa | 30 | 50 | 50 | 56 | 149 | 335 | 
 | Song of India | 43_song_of_india | 0 | 50 | 53 | 50 | 164 | 317 | 
 | Amla | 44_amla | 30 | 51 | 54 | 51 | 92 | 278 | 
 | Blackberry | 45_blackberry | 30 | 51 | 50 | 54 | 71 | 256 | 
 | Spider Plant | 46_spider_plant | 0 | 77 | 70 | 63 | 142 | 352 | 
 | Gold Spot(thin) | 47_gold_spot_thin | 39 | 0 | 50 | 50 | 0 | 139 | 
 | Tangedu | 48_tangedu | 30 | 50 | 50 | 55 | 41 | 226 | 
 | Spider Lily | 49_spider_lily | 0 | 101 | 51 | 50 | 89 | 291 | 
 | Caladium Bicolor | 50_caladium_bicolor | 0 | 24 | 29 | 13 | 149 | 215 | 
 | Snoutbean | 51_snoutbean | 30 | 50 | 51 | 50 | 8 | 189 | 
 | Peacock Flower | 52_peacock_flower | 30 | 52 | 49 | 49 | 114 | 294 | 
 | Paper Leaf | 53_paper_leaf | 30 | 50 | 56 | 0 | 15 | 151 | 
 | Singapore Diasy | 54_singapore_daisy | 30 | 95 | 95 | 50 | 123 | 393 | 
 | Schefflera | 55_schefflera | 30 | 0 | 53 | 51 | 110 | 244 | 
 | Sago Palm | 56_sago_palm | 0 | 56 | 50 | 30 | 147 | 283 | 
 | Castor | 57_castor | 30 | 50 | 53 | 59 | 75 | 267 | 
 | Papaya | 58_papaya | 0 | 44 | 50 | 50 | 65 | 209 | 
 | Butterfly Palm | 59_butterfly_palm | 0 | 53 | 53 | 26 | 124 | 256 | 
 | Foxtail Palm | 60_foxtail_palm | 0 | 53 | 21 | 19 | 76 | 169 | 
 | Mauritius Hemp | 61_mauritius_hemp | 0 | 10 | 13 | 8 | 148 | 179 | 
 | Weeping Fig | 62_weeping_fig | 30 | 51 | 52 | 30 | 131 | 294 | 
 | Banyan | 63_banyan | 34 | 50 | 50 | 49 | 109 | 292 | 
 | Star Cluster | 64_star_cluster | 32 | 50 | 71 | 50 | 112 | 315 | 
 | Dragon Tree | 65_dragon_tree | 0 | 0 | 64 | 76 | 150 | 290 | 
 | Colocasia | 66_colocasia | 0 | 40 | 53 | 62 | 162 | 317 | 
 | Golden Trumphet | 67_golden_trumphet | 32 | 50 | 68 | 20 | 103 | 273 | 
 | Rela | 68_rela | 30 | 56 | 55 | 51 | 46 | 238 | 
 | Ganneru | 69_ganneru | 0 | 7 | 53 | 8 | 69 | 137 | 
 | Gulmohar | 70_gulmohar | 30 | 64 | 54 | 77 | 70 | 295 | 
 | Tulsi | 71_tulsi | 30 | 50 | 101 | 92 | 69 | 342 | 
 | Four'O Clock | 72_four_o_clock | 31 | 60 | 109 | 64 | 66 | 330 | 
 | Air plant | 73_air_plant | 32 | 59 | 61 | 55 | 64 | 271 | 
 | Perfume Flower | 74_perfume_flower | 32 | 65 | 89 | 66 | 47 | 299 | 
 | Badam | 75_badam | 36 | 86 | 60 | 60 | 80 | 322 | 
 | Curry Leaf | 76_curry_leaves | 30 | 50 | 60 | 65 | 44 | 249 | 
 | Insulin | 77_insulin | 0 | 58 | 59 | 15 | 102 | 234 | 
 | Kamala | 78_kamala | 33 | 57 | 60 | 50 | 61 | 261 | 
 | Kanuga | 79_kanuga | 30 | 56 | 65 | 34 | 53 | 238 | 
 | Candle Bush | 80_candle_bush | 33 | 87 | 64 | 51 | 97 | 332 | 
 | Nalleru | 81_nalleru | 32 | 68 | 7 | 58 | 93 | 258 | 
 | Junglee Kikar | 82_junglee_kikar | 0 | 7 | 6 | 5 | 54 | 72 | 
 | Touch Me Not tree | 83_touch_tree | 0 | 53 | 60 | 54 | 100 | 267 | 
 | Etha | 84_etha | 32 | 56 | 59 | 63 | 81 | 291 | 
 | Lipstick tree | 85_lipstic | 30 | 55 | 56 | 44 | 72 | 257 | 
 | Jasmine Arabian | 86_jasmine_arabian | 28 | 57 | 60 | 42 | 26 | 213 | 
 | Sarpagandha | 87_sarpagandha | 31 | 94 | 67 | 55 | 68 | 315 | 
 | Pulla Jemudu | 88_pulla_jemudu | 0 | 0 | 4 | 39 | 79 | 122 | 
 | Pink Paper | 89_pink_paper | 30 | 55 | 57 | 60 | 32 | 234 | 
 | Subabul | 90_subabul | 0 | 0 | 6 | 5 | 77 | 88 | 
 | Canna | 91_canna | 0 | 53 | 46 | 63 | 74 | 236 | 
 | Thorn Apple | 92_thorn_apple | 0 | 7 | 50 | 37 | 97 | 191 | 
 | Pumpkin | 93_pumpkin | 0 | 5 | 6 | 5 | 53 | 69 | 
 | Whistling Pine | 94_whistling_pine | 0 | 0 | 59 | 55 | 82 | 196 | 
 | Royal Palm | 95_royal_palm | 0 | 50 | 50 | 89 | 86 | 275 | 
 | Poinsettia | 96_poinsettia | 0 | 56 | 59 | 32 | 52 | 199 | 
 | Dumbcane | 97_dumbcane | 0 | 56 | 65 | 58 | 92 | 271 | 
 | Parsley | 98_delphinium | 0 | 0 | 19 | 19 | 59 | 97 | 
 | Ti Plant | 99_ti_plant | 0 | 47 | 45 | 45 | 156 | 293 | 
 | Money Plant | 100_money_plant | 31 | 65 | 42 | 63 | 94 | 295 | 
 | Taro | 101_taro | 0 | 22 | 19 | 19 | 155 | 215 | 
 | Allamanda Pink | 102_allamanda_pink | 31 | 59 | 57 | 56 | 42 | 245 | 
 | Zigzag plant | 103_zigzag_plant | 0 | 8 | 5 | 5 | 40 | 58 | 
 | Brinjal | 104_brinjal | 0 | 13 | 14 | 10 | 71 | 108 | 
 | Pink shower | 105_pink_shower | 32 | 61 | 57 | 59 | 81 | 290 | 
 | Indian Tulip | 106_indian_tulip | 30 | 70 | 61 | 62 | 80 | 303 | 
 | Lantana | 107_lantana | 41 | 49 | 79 | 56 | 86 | 311 | 
 | Banana | 108_banana | 0 | 20 | 27 | 31 | 101 | 179 | 
 | Oleander | 109_oleander | 30 | 84 | 48 | 55 | 89 | 306 | 
 | Bamboo | 110_bamboo | 32 | 53 | 72 | 17 | 50 | 224 | 
 | African Milk tree | 111_african_milk_tree | 0 | 0 | 0 | 5 | 60 | 65 | 
 |  **Total**  | **112** | **2454** | **5398** | **5691** | **5021** | **9442** | **28006**








If you are using Indic-Leaf-Dataset, please cite us as the following.

@article{muthireddyindian,
  title={Indian Plant Recognition in the Wild},
  author={Muthireddy, Vamsidhar and Jawahar, CV},
  journal={7th National Conference on Computer Vision, Pattern Recognition, Image Processing and Graphics (NCVPRIPG 2019)},
  year={2019}
}
