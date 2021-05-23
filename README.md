## Weather App

 Weather App is just a basic app to see weather in your nearby cities. 

## Technologies

- Django
- Python
- HTML
- CSS
- WeatherAPI (http://openweathermap.org)

## Getting Started

To get a local copy up and running follow these simple steps:

### Prerequisites

- Python 3.
### Installation

1. Create a local copy of this git repository with `git clone` command.

   ```shell
   $ git clone https://github.com/dhavall13/Weather-App.git
   ```

2. Create a Virtual Enviornment with the `virtualenv` module.

   ```shell
   $ virtualenv .
   ```

3. Once you’ve created a virtual environment, you may activate it.

   ```shell
   $ . activate
   ```

4. Now, install the requirements from the `requirements.txt` file.

   ```shell
   $ pip install -r requirements.txt
   ```

5. Now, apply the migrations with the management command.

   ```shell
   $ python manage.py migrate
   ```

6. Finally, start the developement server with the management command.

   ```shell
   $ python manage.py runserver
   ```

## Usage

You can use this project to see weather in your area. It is simple,clean and easy to use. You should give a try!

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

- Dhaval Chaudhari - *Initial work* - [dhavall13](https://github.com/dhavall13)

## License

This project is licensed under the MIT License - see the [LICENSE.md](../blob/main/LICENSE) file for details