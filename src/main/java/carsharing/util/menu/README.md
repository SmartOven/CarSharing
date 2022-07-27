# Menu architecture

```
MainMenu  |--> ManagerMenu          |--> CompanyChoosingMenu |--> CompanyActionsMenu |--> CreateCarMenu
          |                         |                        |                       |--> back to ManagerMenu
          |                         |                        |--> back to ManagerMenu
          |                         |--> CreateCompanyMenu
          |                         |--> back to MainMenu
          |
          |--> ChoosingCustomerMenu |--> CustomerMenu        |--> ChooseCompanyMenu |--> ChooseCarMenu
          |                         |                        |--> back to MainMenu
          |                         |--> back to MainMenu
          |--> CreateCustomerMenu
          |--> exit
```

## Usage
See [Menu interface class](https://github.com/SmartOven/CarSharing/blob/main/src/main/java/carsharing/util/menu/Menu.java)
