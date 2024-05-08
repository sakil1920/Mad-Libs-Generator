# Mad-Libs-Generator

def mad_libs():
story_tamplate = "The {noun} {verb} {adverb} in the {adjective} park."

    noun = input("Enter a noun: ")
    verb = input("Enter a verb: ")
    adverb = input("Enter a adverb: ")
    adjective = input("Enter a adjective: ")

    mad_lib_story = story_tamplate.format(noun = noun, verb = verb, adverb = adverb, adjective = adjective)

    print("Here's your Mad Lib story:")
    print(mad_lib_story)

mad_libs()
