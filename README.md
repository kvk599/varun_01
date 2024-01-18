# varun_01
config(
    post_hook = """
        -- Your SQL statements or scripts go here
        DROP TABLE IF EXISTS temp_table;
        ANALYZE my_model;
    """
)
