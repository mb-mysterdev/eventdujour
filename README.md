Welcome to the better Eventbrite ♥️ made in Paris by Momo Polo and Yannick

to do list:

bundle install


rails db:create


rails db:migrate


rspec

rails console

u = User.create

e = Event.create

a = Attendance.create(event: e, user: u, stripe_customer_id: "123")
