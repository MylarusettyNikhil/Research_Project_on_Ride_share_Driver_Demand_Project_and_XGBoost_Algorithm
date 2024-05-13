# Ride Share Driver Demand Prediction

## Data Information

Get the data from: [NYC TLC Trip Record Data](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) (2016 data)

The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC).

### Information on Taxis:

- **Yellow Taxi**: Yellow Medallion Taxicabs
  - These are the famous NYC yellow taxis that provide transportation exclusively through street-hails. The number of taxicabs is limited by a finite number of medallions issued by the TLC. You access this mode of transportation by standing in the street and hailing an available taxi with your hand. The pickups are not pre-arranged.
  
- **For Hire Vehicles (FHVs)**:
  - FHV transportation is accessed by a pre-arrangement with a dispatcher or limo company. These FHVs are not permitted to pick up passengers via street hails, as those rides are not considered pre-arranged.
  
- **Green Taxi**: Street Hail Livery (SHL)
  - The SHL program will allow livery vehicle owners to license and outfit their vehicles with green borough taxi branding, meters, credit card machines, and ultimately the right to accept street hails in addition to pre-arranged rides.

*Credits: Quora*

**Footnote:**
In the given notebook, we are considering only the yellow taxis for the time period between Jan - Mar 2015 & Jan - Mar 2016

## ML Problem Formulation

**Time-series forecasting and Regression**

- To find the number of pickups, given location coordinates (latitude and longitude) and time, in the query region and surrounding regions.

To solve the above, we would be using data collected in Jan - Mar 2015 to predict the pickups in Jan - Mar 2016.
