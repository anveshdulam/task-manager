#------------WELCOME TO THE TASK MANGER-------------

def tasks():
    tasks = []
    print('----welcome to task manger----')

    total_tasks = int(input("how many tasks you want to add:"))
    for i in range(1 ,total_tasks + 1):
        task_name = input(f"enter tasks{+i}: ")
        tasks.append(task_name)

        print(f"todays tasks are:\n{tasks}")
        while True:
         operation = int(input("enter 1-add task\n2-delete_task\n3-view tasks\n4-edit_tasks\n5-exit\n6-completed_tasks\n"))
          
         if operation == 1:
            add_task = input("enter the task you wanted to add:")
            tasks.append(add_task)
            print(f"task'{add_task}' has been added successfully")
         
         elif operation == 2:
           delete_task =input("which tasks you wanted to delete:")
           if delete_task in tasks:
              ind = tasks.index(delete_task)
              del tasks[ind]
              print(f'task"{delete_task}" has been deleted successfully...')
           else:
                print('task not found')
         elif operation == 3:
            print(f"\nyour planned tasks are:\n'{tasks}'\n")    
         
         elif operation == 4:
             edit_tasks = input('enter the task you wanted to edit:') 
             if edit_tasks in tasks:  
               ind = tasks.index(edit_tasks) 
               new_task = input('enter the new task name:')
               tasks[ind] = new_task
               print(f'task updated to"{new_task}"')

         elif operation == 5:
                print("remember the tasks of the day\nenjoy the day....")
                break
         elif operation == 6:
                  completed_task = input("which task have you completed:")
                  if completed_task in tasks:
                     tasks.remove(completed_task)
                     print(f'congratulations on completing the task"{completed_task}"')
                  else:
                     print("task not found")
         else:
                print("Invalid Input. Please enter a number from 1 to 5.")
                
tasks()


               
           
       

   


            
