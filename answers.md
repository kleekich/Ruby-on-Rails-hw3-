1. What is the difference between new and create for a model?
	new just does not stored in the database. It is saved when we manually type <User_Object>.save. However, create automatically saves the new instance into the database.
2. What command combined with new will emulate the same behavior as create?
	.save
3. What is the column that exists on every table but we did NOT define?
	id
4. What single line of ruby code can insert a cat with the name "hat" in the database?
	Cat.new name:"hat"
5. What was the most confusing part over the last few weeks?
	Spec does not help me at all
6. How did you like this homework in comparison with the others?
	This one is more clearer