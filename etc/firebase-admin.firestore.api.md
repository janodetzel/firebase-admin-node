## API Report File for "firebase-admin.firestore"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { AddPrefixToKeys } from '@google-cloud/firestore';
import { Agent } from 'http';
import { AggregateField } from '@google-cloud/firestore';
import { AggregateFieldType } from '@google-cloud/firestore';
import { AggregateQuery } from '@google-cloud/firestore';
import { AggregateQuerySnapshot } from '@google-cloud/firestore';
import { AggregateSpec } from '@google-cloud/firestore';
import { AggregateSpecData } from '@google-cloud/firestore';
import { AggregateType } from '@google-cloud/firestore';
import { BulkWriter } from '@google-cloud/firestore';
import { BulkWriterOptions } from '@google-cloud/firestore';
import { BundleBuilder } from '@google-cloud/firestore';
import { ChildUpdateFields } from '@google-cloud/firestore';
import { CollectionGroup } from '@google-cloud/firestore';
import { CollectionReference } from '@google-cloud/firestore';
import { DocumentChange } from '@google-cloud/firestore';
import { DocumentChangeType } from '@google-cloud/firestore';
import { DocumentData } from '@google-cloud/firestore';
import { DocumentReference } from '@google-cloud/firestore';
import { DocumentSnapshot } from '@google-cloud/firestore';
import { FieldPath } from '@google-cloud/firestore';
import { FieldValue } from '@google-cloud/firestore';
import { Filter } from '@google-cloud/firestore';
import { Firestore } from '@google-cloud/firestore';
import { FirestoreDataConverter } from '@google-cloud/firestore';
import { GeoPoint } from '@google-cloud/firestore';
import { GrpcStatus } from '@google-cloud/firestore';
import { NestedUpdateFields } from '@google-cloud/firestore';
import { OrderByDirection } from '@google-cloud/firestore';
import { PartialWithFieldValue } from '@google-cloud/firestore';
import { Precondition } from '@google-cloud/firestore';
import { Primitive } from '@google-cloud/firestore';
import { Query } from '@google-cloud/firestore';
import { QueryDocumentSnapshot } from '@google-cloud/firestore';
import { QueryPartition } from '@google-cloud/firestore';
import { QuerySnapshot } from '@google-cloud/firestore';
import { ReadOnlyTransactionOptions } from '@google-cloud/firestore';
import { ReadOptions } from '@google-cloud/firestore';
import { ReadWriteTransactionOptions } from '@google-cloud/firestore';
import { setLogFunction } from '@google-cloud/firestore';
import { SetOptions } from '@google-cloud/firestore';
import { Settings } from '@google-cloud/firestore';
import { Timestamp } from '@google-cloud/firestore';
import { Transaction } from '@google-cloud/firestore';
import { UnionToIntersection } from '@google-cloud/firestore';
import { UpdateData } from '@google-cloud/firestore';
import { v1 } from '@google-cloud/firestore';
import { WhereFilterOp } from '@google-cloud/firestore';
import { WithFieldValue } from '@google-cloud/firestore';
import { WriteBatch } from '@google-cloud/firestore';
import { WriteResult } from '@google-cloud/firestore';

export { AddPrefixToKeys }

export { AggregateField }

export { AggregateFieldType }

export { AggregateQuery }

export { AggregateQuerySnapshot }

export { AggregateSpec }

export { AggregateSpecData }

export { AggregateType }

export { BulkWriter }

export { BulkWriterOptions }

export { BundleBuilder }

export { ChildUpdateFields }

export { CollectionGroup }

export { CollectionReference }

export { DocumentChange }

export { DocumentChangeType }

export { DocumentData }

export { DocumentReference }

export { DocumentSnapshot }

export { FieldPath }

export { FieldValue }

export { Filter }

// Warning: (ae-forgotten-export) The symbol "FirebaseError" needs to be exported by the entry point index.d.ts
//
// @public
export class FirebaseFirestoreError extends FirebaseError {
}

export { Firestore }

export { FirestoreDataConverter }

// @public
export interface FirestoreSettings {
    preferRest?: boolean;
}

export { GeoPoint }

// @public
export function getFirestore(): Firestore;

// Warning: (ae-forgotten-export) The symbol "App" needs to be exported by the entry point index.d.ts
//
// @public
export function getFirestore(app: App): Firestore;

// @beta
export function getFirestore(databaseId: string): Firestore;

// @beta
export function getFirestore(app: App, databaseId: string): Firestore;

export { GrpcStatus }

// @public
export function initializeFirestore(app: App, settings?: FirestoreSettings): Firestore;

// @beta
export function initializeFirestore(app: App, settings: FirestoreSettings, databaseId: string): Firestore;

export { NestedUpdateFields }

export { OrderByDirection }

export { PartialWithFieldValue }

export { Precondition }

export { Primitive }

export { Query }

export { QueryDocumentSnapshot }

export { QueryPartition }

export { QuerySnapshot }

export { ReadOnlyTransactionOptions }

export { ReadOptions }

export { ReadWriteTransactionOptions }

export { setLogFunction }

export { SetOptions }

export { Settings }

export { Timestamp }

export { Transaction }

export { UnionToIntersection }

export { UpdateData }

export { v1 }

export { WhereFilterOp }

export { WithFieldValue }

export { WriteBatch }

export { WriteResult }

```
