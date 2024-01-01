
# Goal Setter App *(in development)*

A REST API based goal setter app which sets the goals of users. ***(not complete in development)***

My very first MERN project while learning it.

## Pre-Requisites
Languages:
- JavaScript
- CSS
- HTML

##### You also need a MongoDB account with a database created to use this on your machine.

## Installation and Usage

### Cloning the repository

You can clone the repository using the following command:

```
git clone https://github.com/SleepyMiner/GoalSetterApp.git
```
### Installing dependencies

After cloning the repository, navigate to the project directory and install the dependencies by running the following command:
```
npm install
```

### Running the project

To run the project, run the following command:

```
npm run server
```

This will start the development server and the application can be accessed through a web browser at  `http://localhost:5000/`.

## Usage

#### Get and Post Request Endpoint
```
http://localhost/api/goals
```
#### Update and Delete Request Endpoint
```
http://localhost/api/goals/:id
```
>The "id" field should be replaced with the id of the document in the database which needs to be updated.

>We would get all the goals in the database as per the user. *(The user part is in development)*
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
