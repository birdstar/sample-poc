# Sample Data ReadMe

## CSV field explanation

* vin: Unique ID of each vehicle
* city: city where the vehicle resides, e.g. Beijing
* date: date of the vehicle, e.g. format: 2018-06-27
* start_timestamp: start timestamp of all the data aggravate, e.g. 1518047312000 (millsec)
* end_timestamp: end timestamp of all the data aggravate
* sum_mileage: sum of the mileage during the start-end timestamp
* avg_speed: sum_mileage/(end_timestamp - start_timestamp)
* car_type: car type series e.g. S350, S320...
* prod_year: the year of the vehicle produced

---

* sum_app_xxx: sum of the count for app service used during the start-end timestamp
sum_app_park_man,
sum_app_player,
sum_app_radio,
sum_app_navi,
sum_app_vehicle,
sum_app_tel,
sum_app_car_play,
sum_app_connect_menu,
sum_app_system_settings,
sum_app_diba,
sum_app_mb_apps,
sum_app_browser,

* sum_hardkey_xxx: sum of the count for hardkey used during the start-end timestamp
sum_hardkey_back,
sum_hardkey_menu,
sum_hardkey_mute,
sum_hardkey_end,
sum_hardkey_send,
sum_hardkey_volume_up,
sum_hardkey_volume_down,
sum_hardkey_media,
sum_hardkey_on,
sum_hardkey_navi,
sum_hardkey_radio,
sum_hardkey_ptt,
sum_hardkey_bga,
sum_hardkey_car,
sum_hardkey_phone,
sum_hardkey_seat,
sum_hardkey_favorite,
sum_hardkey_skip_fw,
sum_hardkey_skip_bw,
sum_hardkey_play_pause,
sum_hardkey_web
