# data-manipulation-ooi
These python scripts were developed for the Ocean Observatories Initiative (OOI) data review team to manipulate asset management data sheets.


###Scripts
- [appendCSV.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/appendCSV.py): Combines all ingest csvs.

- [append_cal_sheets_mooringinfo.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/append_cal_sheets_mooringinfo.py): Combines the first sheet (called 'Moorings') of archived OOI cal sheets.

- [check_deployment_UIDs.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/check_deployment_UIDs.py): Tests for a match between the instrument in the Reference Designator and the sensor.uid.

- [check_system_refdes_stream.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/check_system_refdes_stream.py): Compares the reference designators and streams in the QC database to uFrame and the GUI data catalog list.

- [check_system_refdes.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/check_system_refdes.py): Compares the master list of reference designators in the vocab.csv to the reference designators ingested in uFrame.

- [compare_qcdb_vocab.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/compare_qcdb_vocab.py): Compares the master list of reference designators in the asset management vocab.csv to the reference designators in the data team's QC database.

- [ingest_csvs_extract_instrument.py](https://github.com/lgarzio/data-manipulation-ooi/blob/master/ingest_csvs_extract_instrument.py): Creates new ingest csvs for a specific instrument in a platform directory from https://github.com/ooi-integration/ingestion-csvs. Useful when needing to purge and re-ingest all deployments of a specific instrument for a platform.