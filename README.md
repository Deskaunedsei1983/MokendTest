# MokendTest
# 1. List your fake users with a GET request
curl https://mockend.com/org/repo/users

# 2. Fake a creation with a POST
# (don't worry changes aren't persisted)
curl https://mockend.com/org/repo/users \
  -X POST \
  -H "Content-Type: application/json" \
  --data '{"name": "alice"}'

# 3. Access your GraphQL endpoint
https://mockend.com/org/repo/graphql

Config
.mockend.json
REST examples
https://mockend.com/mockend/demo/posts
https://mockend.com/mockend/demo/posts/1
https://mockend.com/mockend/demo/posts?createdAt_order=desc
https://mockend.com/mockend/demo/posts?tag_eq=one
GraphQL examples
https://mockend.com/mockend/demo/graphql?query=...
