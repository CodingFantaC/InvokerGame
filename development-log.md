Thursday 23 April 2020
-Implemented multi line string for game title/intro, using ASCII art
-Implemented main menu list/options
-Implemented user input for main menu list, using get.chomp method.
-Issue with infinite loop/error message with invalid input and trying to "quit"
-Fixed issue with infinite loop/error message
-Added .downcase method to user_input = gets.chomp, in intro_menu_choice to ignore case sensitivity for user experience.
-Added message on user input "quit"
-Tested for any errors or bugs in intro_menu and intro_menu_choice, none found
-created show_info.rb file, added INFO ascii art and list of options and input.
-Added show_info and show_info_choice methods to show_info.rb file. 
-Created link path between invoker_game.rb and show_info.rb using Ruby load method
-Added system('clear') for better user interface/experience when transitioning to different sections
-Fixed being unable to exit game(loop) with 'quit' input when going to info and back to title/menu. included exit (line 44)
-Finished how_to_play.rb page
-Finished INFO section, including HOW TO PLAY and ABOUT INVOKER, transitions working as intended.

Saturday 25 April 2020
-Started development on play ENDLESS game mode
-Created invoke_list for spells
-Stuck on figuring logic to randomize + user answer input in ENDLESS mode