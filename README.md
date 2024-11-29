# Big Data CS GY 6513 Assignment 3

This assignment tests your knowledge of MongoDB.

## Setup MongoDB

To set up MongoDB using Docker, follow these steps:

1. Ensure you have Docker installed on your machine.
2. Run the following command to start MongoDB in a Docker container:

   ```sh
   docker-compose up -d
   ```

## Execute the Notebook

To execute the Jupyter Notebook, follow these steps:

1. Ensure you have Jupyter installed on your machine.
2. Open a terminal and navigate to the directory containing the notebook.
3. Run the following command to start Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

4. In the Jupyter Notebook interface, open `ds8106-HW4.ipynb` and execute the cells.

## Notes

- Ensure that the `data` directory contains the necessary JSON and CSV files for the assignment.
- The MongoDB container should be running before executing the notebook cells that interact with the database.
- If you encounter any issues, check the Docker logs for the MongoDB container:

  ```sh
  docker-compose logs
  ```
