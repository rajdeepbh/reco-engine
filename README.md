# mreco

[mreco](https://mreco.herokuapp.com/) is a Movie Recommendation System that leverages machine learning algorithms based on:

- User-user collaborative filtering
- Item-item collaborative filtering
- Dimensionality Reduction (Matrix Factorization)

### Getting started

Install a virtual environment on [mac/linux](https://www.codingforentrepreneurs.com/blog/install-django-on-mac-or-linux/) or [windows](https://www.codingforentrepreneurs.com/blog/install-python-django-on-windows)

```
$ pip install -r requirements.txt
```

Install [MongoDB](https://docs.mongodb.com/manual/installation/) and start a [mongod process](https://docs.mongodb.com/manual/tutorial/manage-mongodb-processes/). Use the collection dump provided in the repository.

Set environment variables:

```
$ export FLASK_ENV=development
$ export FLASK_APP=mreco
```

Run the app:

```
$ flask run
```

### Dependencies

- Flask (python web framework)
- MongoDB (document store)
- mongoengine (Document-Object Mapper)
- scikit-learn, pandas, numpy, scipy (for machine learning and data cleaning)
- mlab (Database-as-a-Service for MongoDB, used in production)
- Heroku (Cloud Application Platform)
- Bootstrap (Frontend Framework)

### Credits

Inspired by this [blog post](https://towardsdatascience.com/the-4-recommendation-engines-that-can-predict-your-movie-tastes-109dc4e10c52)
