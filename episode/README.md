# Character Queries

This folder contains GraphQL queries and their outputs for retrieving specific character information by ID from the Rick and Morty GraphQL API.

**Endpoint:**



**Query Fields:**
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

**Characters queried:**
- ID 1: Rick Sanchez
- ID 2: Morty Smith
- ID 3: Summer Smith
- ID 4: Beth Smith

## 1. Write a Query to Get a List of All Characters

Objective: Learners will create a GraphQL query to retrieve a paginated list of all characters.

Instructions:

Write a GraphQL query using the characters(page: Int) field to fetch the list of characters. For page 1, 2, 3, 4
Select the subfields: id, name, status, and image.

## 2. Write a Query to Get a Specific Episode by ID


Objective: Learners will write a GraphQL query to fetch the details of a specific episode using its ID.

Instructions:

Write a GraphQL query using the episode(id: ID!) field to retrieve details of an episode.
Include the following fields in your query: id, name, air_date, episode