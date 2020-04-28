{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Step By Step Walk-through"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## 1. We looked through the data in order to figure out what tables we would need for this database.\n",
    "    - We found that Cataloge Courses and Section would be the most important and largest entities\n",
    "    - As for other tables we settled on Location, Term, Section Mettings, intructors and programs\n",
    "    - With this in mind we normalized the database and created an ERD\n",
    "    \n",
    "## 2. Next we created and populated the Database\n",
    "    - Each table was created and primary and forgien keys wetre specified\n",
    "    - Utilizing Python we were able to create import tables in order to more effciently import the data\n",
    "    - Before importing we checked the counts of each table to make sure it was accurate\n",
    "    - Lastly, using the import tables we were able to fully populate the database\n",
    "    \n",
    "## 3. Once the Database was created we checked for intergirty\n",
    "    - Did a few tests to check for relational, entity, and domain integrity\n",
    "    \n",
    "## 4. Next we contructed the Data Warehouse\n",
    "    - Using the Star Schema model we chose Section Meetings to be our fact table\n",
    "    - The Dimension tables chosen were Programs, Terms, Locations, TimeCodes and Intsructors\n",
    "    - The tables were all created and PK and FK laid out\n",
    "    - Using the Attach database function we were able to take the CourseDB and use it to populate the warehouse\n",
    "    \n",
    "## 5. Next we needed to test the Warehouse for intergirty \n",
    "    - "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
