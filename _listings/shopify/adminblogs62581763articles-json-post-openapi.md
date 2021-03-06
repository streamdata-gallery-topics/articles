---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Create a new article for a blog
  description: Create a new article for a blog.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/blogs/62581763/articles.json:
    get:
      summary: Get a list of all articles from a certain blog
      description: Get a list of all articles from a certain blog.
      operationId: getAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Articles
      - From
      - Certain
      - Blog
    post:
      summary: Create a new article for a blog
      description: Create a new article for a blog.
      operationId: postAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Articlea
      - Blog
  /admin/blogs/62581763/articles/count.json:
    get:
      summary: Get a count of all articles from a certain blog
      description: Get a count of all articles from a certain blog.
      operationId: getAdminBlogs62581763ArticlesCount.json
      x-api-path-slug: adminblogs62581763articlescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Articles
      - From
      - Certain
      - Blog
  /admin/articles/tags.json:
    get:
      summary: Get a list of all the tags of articles
      description: Get a list of all the tags of articles.
      operationId: getAdminArticlesTags.json
      x-api-path-slug: adminarticlestags-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Tags
      - Articles
  /admin/blogs/62581763/articles/197247246.json:
    delete:
      summary: Delete an article of a blog tags of articles
      description: Delete an article of a blog tags of articles.
      operationId: deleteAdminBlogs62581763Articles197247246.json
      x-api-path-slug: adminblogs62581763articles197247246-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
      - Blog
      - Tags
      - Articles
  /admin/articles/authors.json:
    get:
      summary: Get a list of all the authors of articles
      description: Get a list of all the authors of articles.
      operationId: getAdminArticlesAuthors.json
      x-api-path-slug: adminarticlesauthors-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Authors
      - Articles
  /admin/blogs/62581763/articles/196805774.json:
    get:
      summary: Get a single article by its ID and the ID of the parent blog
      description: Get a single article by its id and the id of the parent blog.
      operationId: getAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Article
      - By
      - Its
      - ID
      - ID
      - Parent
      - Blog
    put:
      summary: Update an article
      description: Update an article.
      operationId: putAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
  //admin/comments.json:
    post:
      summary: Create a new comment for an article
      description: Create a new comment for an article.
      operationId: postAdminComments.json
      x-api-path-slug: admincomments-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Commentan
      - Article
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---