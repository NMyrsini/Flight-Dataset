# Flight-Dataset
Historical Flight data

This is a .txt file containing historical flight data gathered using a Python scrapper from expedia.com in 2018. It can be utilizied for time series forecasting (e.g., flight price prediction). The dataset consists of 26 routes. All routes depart from several European cities as: Amsterdam, Berlin, Brussels, Eindhoven, Frankfurt, Geneva, London, Milan, Munich, Paris, Prague, Stockholm, Zurich. The arrival cities are Athens and Thessaloniki, Greece. The data are ordered with respect to the scapping date, from the older to the newer ones. Each row corresponds to a certain route scrapped at a certain date. They are comma-separated entities corresponding to:

days_until_flight, route_name, scrapping_date, departure_city, arrival_city, departure_time, arrival_time, day_of_week(1=Monday - 7=Sunday), number_of_stops, flight_date, flight_duration(minutes), holiday(0/1), overnight(0/1), ticket_price(in euros)

Example: 
43,Amsterdam_Thessaloniki,07_13_2018,Amsterdam,Thessaloniki,9:10pm,3:25pm,5,1,08/25/2018,1035,0,0,258

Please notice that the scrapping date format is DD_MM_YYYY and the flight date format is MM/DD/YYYYY.

Please cite as:

@article{ntemi2020dynamic,
  title={A dynamic dyadic particle filter for price prediction},
  author={Ntemi, Myrsini and Kotropoulos, Constantine},
  journal={Signal Processing},
  volume={167},
  pages={https://doi.org/10.1016/j.sigpro.2019.107334},
  year={2020},
  publisher={Elsevier}
}




 
