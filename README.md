# QBCore Food Ordering System

A self-ordering food system for QBCore FiveM servers that allows players to order food from designated locations. This resource provides a user-friendly interface for players to browse and purchase food items.

## Features

- 🍔 Interactive menu system with food items and prices
- 🎨 Customizable UI with sound effects
- 💰 Configurable prices and items
- 🎯 Easy to set up target location
- 🏪 Job-restricted access (configurable)
- 📱 Responsive design that works on all screen sizes

## Installation

1. Download the latest release
2. Place the `qb-foodorder` folder in your server's `resources` directory
3. Add `ensure qb-foodorder` to your server.cfg
4. Restart your server

## Configuration

Edit the `config.lua` file to customize the following:

- Set the target location coordinates
- Enable/disable UI sounds
- Change the total price color (red, blue, or green)
- Set the job name that can access the food order system
- Add/remove food items with custom images and prices

## Dependencies

- [QBCore Framework](https://github.com/qbcore-framework)
- [oxmysql](https://github.com/overextended/oxmysql)
- [qb-target](https://github.com/BerkieBb/qb-target) 

## Preview
Ordering Panel
<img width="1725" height="977" alt="Screenshot_3" src="https://github.com/user-attachments/assets/90a9b37f-6449-437a-8b1f-4ba72208e6ac" />
Ordering Panel(Added to Cart)
<img width="1476" height="925" alt="Screenshot_1" src="https://github.com/user-attachments/assets/962b8b83-6741-44cb-a307-1de5d65c4aca" />
Order List
<img width="2144" height="880" alt="Screenshot_2" src="https://github.com/user-attachments/assets/d4b7a58f-df27-4e92-915e-9b112f45bc18" />
Management Panel
<img width="2139" height="803" alt="Screenshot_4" src="https://github.com/user-attachments/assets/1a00574b-a8f7-4010-b249-f770590231ea" />


## License

This project is licensed under the MIT License.

## Credits

- devtakkekar - Initial work
- QBCore Framework Team
