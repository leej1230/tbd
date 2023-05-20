# Do It'er
## Find motivation through sharing your goals and accomplishments
# Data Schema
```
{
    "ToDo": [
        {
            "todo_id": ObjectId,
            "text": String,
            "cnt_used": Integer,
            "cnt_done": number
        }
    ],
    "Post": [
        {
            "post_id": ObjectId,
            "user_id": ObjectId,
            "created": Date,
            "todo_list": ObjectId[],
            "checked": Boolean[]
        }
    ],
    "User": [
        {
            "user_id": String,
            "name": String,
            "email": String,
            "register_date": Date,
            "bookmarked_todo": ObjectId[]
        }
    ]
}
```