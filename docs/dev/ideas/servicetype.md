
# the type of service
  * DataBase for anything related with KBS
  * Lite Chat system with other members

# details - database
  * contains -- list of properties of KBS, lecture for each properties, status of properties, logs of each events, breakdown log, trouble log.
  * what to aim -- make sure what are there. make sure what we can use. make sure all of us can use them.

    properties list has below                lecture has below                                 
      | its name                               | target name
      | its photo                              | date when it written
      | its description                        | author(name,role)                       
      | its status(broken?usable?)             | lecture itself(can contains photo)                 
      | (optional) path to its manual          | comment field                                         
  
    status of properties has below
      | property name
      | date to registered
      | detail (what's the problem,like "don't sound anything")
      | can be fixed or not
  
    log of each events has below
      | date, time, event name, where was the event hold
      | members(only numbers of people, ex: PA - 2, Floor L - 5, Floor R - 5)
      | good point
      | bad point
      | Floor map

    breakdown/broken log has below
      | summary
      | date, writer name
      | the target name
      | detail
      | (optional) request to fix
      | status (is it done?not yet?)
      | (if already fixed) what was bad thing, how fixed it

    trouble log has below 
      | trouble summary
      | date,writer
      | target name
      | detail
      | status (done or yet)
      | (if it's done) what was bad, how solve the problem
