set(SOURCES "") # avoid pulling SOURCES from parent scope

lagom_tool(GenerateCSSEnums                SOURCES GenerateCSSEnums.cpp LIBS LagomMain)
lagom_tool(GenerateCSSMediaFeatureID       SOURCES GenerateCSSMediaFeatureID.cpp LIBS LagomMain)
lagom_tool(GenerateCSSPropertyID           SOURCES GenerateCSSPropertyID.cpp LIBS LagomMain)
lagom_tool(GenerateCSSTransformFunctions   SOURCES GenerateCSSTransformFunctions.cpp LIBS LagomMain)
lagom_tool(GenerateCSSValueID              SOURCES GenerateCSSValueID.cpp LIBS LagomMain)

add_subdirectory(WrapperGenerator)
