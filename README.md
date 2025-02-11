# Pilot Log

This is a simple general aviation private pilot logbook web application, geared towards those of us frequently flying multiple types of light aircraft.

It is being developed to provide a personal migration path from the excellent [FlightLog](http://warbredstudios.com/flightlog/flightlog.html) for Android software by Jeff Cardillo and released in the hope that it will be useful to other private pilots.

## Requirements

* Python
* Django

## Usage

```
./manage.py migrate
./manage.py createsuperuser
```

```
./manage.py dumpdata logbook --exclude logbook.Aerodrome --exclude logbook.LogEntry > logbook/fixtures/logbook.json
```

```
./manage.py loaddata logbook
```

## License

This project is released under the terms of the MIT license. Full details in the `LICENSE` file.
