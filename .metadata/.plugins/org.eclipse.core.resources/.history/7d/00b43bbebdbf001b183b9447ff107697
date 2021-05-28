package coffeeShop;

import java.time.LocalDate;

import Abstract.BaseCustomerManager;
import Adapters.MernisServiceAdapter;
import Concrete.StarbucksCustomerManager;
import Entities.Customer;



public class Main {

	public static void main(String[] args) {

		BaseCustomerManager customerManager=new StarbucksCustomerManager(new MernisServiceAdapter());
		customerManager.save(new Customer(1,"Filiz","Gül",LocalDate.of(1993,01,01),"12345678910"));
	}

}
