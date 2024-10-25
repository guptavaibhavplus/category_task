# category_task



# COURSE MODULE SCHEMA:
# Course: {
#    _id: { type: ObjectId }
#     name: { type: String };
#     categories: [{ type: ObjectId, ref: 'category' }]
#      subCategories: [{ type: ObjectId, ref: 'SubCategory' }]
#}

# At the Course schema level, categories and subcategories need to be assigned and updated
# 1. Implement categories and subcategories modules in NestJS Framework (add, edit, retrieve, list with valid all conditions) 
# 2. Write a query listing all categories with subcategory counts for each category, the results will look like below

# Name	     SubCategoryCount
# Category1	 20
# Category2	 5
# Category3	 11
