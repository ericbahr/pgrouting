# Append in local scope
LIST(APPEND PACKAGE_SQL_FILES
    ${CMAKE_CURRENT_SOURCE_DIR}/test_ch_edges.sql
    ${CMAKE_CURRENT_SOURCE_DIR}/testXYedges.sql
    ${CMAKE_CURRENT_SOURCE_DIR}/test_matrixRows.sql
)

# set in parent scope
SET(PACKAGE_SQL_FILES "${PACKAGE_SQL_FILES}" PARENT_SCOPE)
