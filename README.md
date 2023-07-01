# session34-task

Nodejs hall booking api task https://docs.google.com/document/d/1rwPQ2LbHtMZajA_GIZfR-Ko2MFueoT82AmfHTK9V-hM/edit

[Backend Demo](https://hallbooking-api-fhu2.onrender.com)

<h1>HallBooking</h1>
</ hr>
API Documentation

1. Create Hall: POST- https://hallbooking-api-fhu2.onrender.com/halls ex:{
    room_id: 1,
    room_name: "Room 1",
    amenities: ["AC", "CCTV", "STAGE"],
    noSeats: 100,
    room_fee_perhour: 1500,
  }

2. View Halls: GET- https://hallbooking-api-fhu2.onrender.com/halls

3. Create Order: POST- https://hallbooking-api-fhu2.onrender.com/bookings ex: {
    room_id: 2,
    customer_name: "Tripathi",
    date: "14 Jan 2020",
    startTime: "10:00am",
    endTime: "15:00pm",
  }

4. View Orders: GET- https://hallbooking-api-fhu2.onrender.com/bookings

