import Data.List
import System.IO

main = do
    
    putStrLn "Degrees in Fahrenheit?"
    degreesF <- getLine
    convert :: Float -> Float
    convert degreesF = ((degreesF - 32) * 5 / 9)
    putStrLn ("That converts to " ++ (degreesF) ++ " C.")
