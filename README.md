# Feedback for Prisma Admin

This repository is the central place to collect feedback and issues related to [Prisma Admin](https://www.prisma.io/admin).

Please [**open an issue**](https://github.com/prisma/prisma-admin-feedback/issues/new) if you want to leave feedback.

## Custom views
Custom views is powerful extension of prisma-admin. Custom views grants user to extend how to display different types of data. 

### Custom view example

![](https://i.imgur.com/yZ8MosF.png)

### How custom views works

Custom view is iframe what renders your custom view. Prisma admin provides data to iframe trought query string. `${url}?data=${JSON.stringify(data)}`. Its possible to have multiple view for single query. Here is basic [example](https://github.com/Huvik/Custom-view) for json custom view.

### How to add custom view

1. Execute query
2. Select row and in details view on right side click on small eye
3. Add a view 
4. ![](https://i.imgur.com/2HnfTDG.png)
5. Add custom view `name` and `url`
6. New view is added to list
