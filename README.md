# Do It'er
## Find motivation through sharing your goals and accomplishments
# Data Schema
```
{
    "ToDo": [
        {
            "todo_id": String,
            "text": String,
            "cnt_used": Integer,
            "cnt_done": number
        }
    ],
    "Post": [
        {
            "post_id": String,
            "user_id": String,
            "created": Date,
            "todo_list": String[],
            "liked_users": String[],
            "checked": Boolean[]
        }
    ],
    "User": [
        {
            "user_id": String,
            "name": String,
            "email": String,
            "registered_date": Date,
            "liked_posts": String[]
        }
    ]
}
```