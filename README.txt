Brosky: An app for keeping track of gym progress

Currently the planned data structure is as follows:

	Workout
		Exercise[]
			Set[]

Where we have the Workout as the base abstraction for each trainning session.
On each Workout there can be one or more Exercise(s)
Each Exercise can have atleast one Set made in it.
Each Exercise can be repeated on any amount of the Workout(s)
Each Set belongs to an Exercise
Each Set is related to a Workout on which it was made
