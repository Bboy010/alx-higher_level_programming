# 0x0F-python-object_relational_mapping

- Use the module `MySQLdb`to connect to a MySQL database and execute your SQL queries.
- Use the module `SQLAlchemy`an Object relational Mapper (ORM)

## Tasks :heavy_check_mark:

* **0. Get all states**
  * [0-select_states.py](./0-select_states.py): script that lists all states from the database hbtn_0e_0_usa.

* **1. Filter states**
  * [1-filter_states.py](./1-filter_states.py): script that lists all states with a name starting with N (upper N) from the database hbtn_0e_0_usa

* **2. Filter states by user input**

  * [2-my_filter_states.py](./2-my_filter_states.py): script that takes in an argument and displays all values in the states table of hbtn_0e_0_usa where name matches the argument.


* **3. SQL Injection...**
* [3-my_safe_filter_states.py](./3-my_safe_filter_states.py): write a script that takes in arguments and displays all values in the states table of hbtn_0e_0_usa where name matches the argument. But this time, write one that is safe from MySQL injections!

* **4. Cities by states**
* [4-cities_by_state.py](./4-cities_by_state.py): script that lists all cities from the database hbtn_0e_4_usa

* **5. All cities by state**
* [5-filter_cities.py](./5-filter_cities.py): script that takes in the name of a state as an argument and lists all cities of that state, using the database hbtn_0e_4_usa.

* **6. First state model**
* [model_state.py](./model_state.py): Write a python file that contains the class definition of a State and an instance Base = declarative_base().

* **7. All states via SQLAlchemy**
* [7-model_state_fetch_all.py](./7-model_state_fetch_all.py): script that lists all State objects from the database hbtn_0e_6_usa.

* **8. First state**
* [8-model_state_fetch_first.py](./8-model_state_fetch_first.py): script that prints the first State object from the database hbtn_0e_6_usa.
* **9. Contains `a`**
* [9-model_state_filter_a.py](./9-model_state_filter_a.py): script that lists all State objects that contain the letter a from the database hbtn_0e_6_usa.

* **10. Get a state**
* [10-model_state_my_get.py](./10-model_state_my_get.py):  script that prints the State object with the name passed as argument from the database hbtn_0e_6_usa.

* **11. Add a new state**
* [11-model_state_insert.py](./11-model_state_insert.py): script that adds the State object “Louisiana” to the database hbtn_0e_6_usa.

* **12. Update a state**
* [12-model_state_update_id_2.py](./12-model_state_update_id_2.py): script that changes the name of a State object from the database hbtn_0e_6_usa.

* **13. Delete states**
* [13-model_state_delete_a.py](./13-model_state_delete_a.py): script that deletes all State objects with a name containing the letter a from the database hbtn_0e_6_usa.

* **14. Cities in state**
* [14-model_city_fetch_by_state.py](./14-model_city_fetch_by_state.py): write a script 14-model_city_fetch_by_state.py that prints all City objects from the database hbtn_0e_14_usa.
* [model_city.py](./model_city.py): Write a Python file similar to model_state.py named model_city.py that contains the class definition of a City.

* **15. City relationship**
* [relationship_city.py](./relationship_city.py)
* [relationship_state.py](./relationship_state.py)
* [100-relationship_states_cities.py](./100-relationship_states_cities.py)
:Write a script that creates the State “California” with the City “San Francisco” from the database hbtn_0e_100_usa: (100-relationship_states_cities.py)
 
* **16. List relationship**
* [101-relationship_states_cities_list.py](./101-relationship_states_cities_list.py): script that lists all State objects, and corresponding City objects, contained in the database hbtn_0e_101_usa.

* **17. From city**
* [102-relationship_cities_states_list.py](./102-relationship_cities_states_list.py):  script that lists all City objects from the database hbtn_0e_101_usa.

### Hongo on 18 april 2023.

